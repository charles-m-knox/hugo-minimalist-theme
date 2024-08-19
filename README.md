# hugo-minimalist-theme

This is a barebones theme for Hugo that is intended to work without javascript and features minimal CSS.

It's intended to be used in low-RAM browsers like Dillo/DilloPlus, but still looks relatively good in full-featured browsers.

It supports dark/light mode theming - the color scheme is just black and white or vice versa.

## Example configuration

Please see `config.example.yml`.

## Other notes

This theme is probably missing some features that other themes might have. That's part of the goal - I wanted to start from scratch and build only what's needed.

It includes a `{{< rawhtml >}}<p>test</p>{{</ rawhtml >}}` shortcode that allows you to insert arbitrary HTML code (note that it isn't sanitized via `safeHTML`).
