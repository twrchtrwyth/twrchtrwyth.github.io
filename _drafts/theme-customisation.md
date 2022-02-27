To customise the theme, copy the relevant file from the theme's gem folder into the equivalent directory within the Jekyll folder.

In the case of *minima*, the gem folder can be shown by running:

```bash
bundle show minima
```

The `_layouts` directory contains files that define the markup for the theme. For example:

- `default.html` contains the base layout, from which other themes are derived
- `home.html` defines the layout of the home page
  * All content from `index.md` is injected before the **Posts** heading of `home.html` 
- `page.html` defines the layout for documents containing front matter, which are *not* posts
- `post.html` defines the layout of documents marked as "posts" within their front matter
