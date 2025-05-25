# Zola Folio Theme

A Zola theme based on the Jekyll *folio theme.

This theme is a port of the beautiful [*folio theme](http://bogoli.github.io/-folio/) by Lia Bogoev.

[Live Demo](https://zola-folio.pages.dev/)

## Installation

1. Download the theme to your `themes` directory:
   ```bash
   git clone https://github.com/evjrob/zola-folio.git themes/zola-folio
   ```
2. Enable the theme in your `config.toml`:
   ```toml
   theme = "zola-folio"
   ```

This theme requires Zola version 0.19.2 or higher.

## Configuration

You can customize the theme by setting the following variables in your `config.toml`:

- `menu_items`: A list of menu items to display in the header. Each item should have a `name` and a `url`.
- `theme_color`: The color scheme to use for the theme. Available options are "red", "blue", "green", and "purple".
- `author`: The name of the author to display in the footer.
- `show_only_description`: If set to `true`, only the description will be shown on the homepage, otherwise the full content of `_index.md` will be shown.


Example `config.toml` snippet:

```toml
[extra]
menu_items = [
    {name = "about", url = "/pages/about"},
    {name = "projects", url = "/pages/projects"},
    {name = "photography", url = "/pages/photography"},
]
theme_color = "red"
author = "Your Name"
show_only_description = true
```

## Author

Everett Robinson
[http://everettsprojects.com](http://everettsprojects.com)

## License

This theme is released under the MIT License.

## Screenshot

![Screenshot of zola-folio theme](screenshot.png)
