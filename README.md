

# Misc scripts

This is a collection of miscellaneous scripts I call in my `PATH` to help with various tasks. I've just started this repo and will slowly copy over stuff.

**TOC**

- `jpost` Creates a jekyll post with standard `yml` for my blog. At the very least it needs a title with the ``--title` flag. It defaults to current date in the `yml` and filename.
Adding a category drops it into the correct `_posts` folder, especially if you have more than one blog setup in the same root. In my case, the default is `notes`, but can also be `longform` or `reading`. You can change these to how your blog is setup, or just change it to `_posts` if that's in the root.
