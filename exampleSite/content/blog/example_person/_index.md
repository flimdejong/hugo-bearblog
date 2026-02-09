+++
title = "Author Name"  # The display name for the author page
layout = "list"        # Tells Hugo this is a list of posts

[cascade]
  # This is the magic part. It forces the URL for every post in this folder.
  # If the file is 'my-post.md', the URL becomes /blog/author-name/my-post/
  url = "/blog/author-name/:filename/"
  
  # This ensures the 'author' field is set for every post automatically
  authors = ["author-name"]
+++