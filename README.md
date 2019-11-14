# Sublime text custom config

Somewhere to keep a record of my Sublime Text preferences and list the packages I install.


## Packages

These are all installed via Package Control unless otherwise stated. If you don't already have it [Package Control itself should be installed](https://packagecontrol.io/installation) before going any further.

- ApacheConf
- Bump
- Color Highlighter
- EditorConfig
- Emmet
- Handlebars
- JSON Key-Value
- MarkdownEditiing
- nginx
- nunjucks-extended (install [directly from repo](https://github.com/thecodechef/nunjucks-extended))
- One Dark Color Scheme
- Package Control
- Project Specific Syntax Settings
- ProjectManager
- PyV8
- Sass
- SublimeLinter-contrib-scss-lint
- Theme - Monokai Pro
- TOML
- TypeScript


## Preferences, etc.

For preferences, see `Preferences.sublime-settings` in this repo, located at `~/Library/Application Support/Sublime Text 3/Packages/User/`

For keybindings, see `Default (OSX).sublime-keymap` in this repo, located at `~/Library/Application Support/Sublime Text 3/Packages/User/`


## Package config

Many of these packages have their own configuration. The config files are in this repo and should be added to `~/Library/Application Support/Sublime Text 3/Packages/User/`.

### Color Highlighter

If not already installed, run `brew install ImageMagick`, which gets the gutter icons working. From the (annoying) series of dropdown menus, choose the following:

- Tools → Color Highlighter → Color Highlighters → Highlight colors in selected text → Inline highlighting style → Filled
- Tools → Color Highlighter → Color Highlighters → Highlight colors in all text → Inline highlighting style → Text
- Tools → Color Highlighter → Color Highlighters → Highlight colors in all text → Gutter icon style → Circle

All the rest should be 'None'.

See `ColorHighlighter.sublime-settings` file in this repo, which should live in `~/Library/Application Support/Sublime Text 3/Packages/User/ColorHighlighter.sublime-settings`

### MarkdownEditing

Bold and italic markers are `_` and `__` by default. This should be overridden to `*` and `**` in `Bold and Italic Markers.tmPreferences` (file in this repo), which should live in `~/Library/Application Support/Sublime Text 3/Packages/User/Bold and Italic Markers.tmPreferences`

The editor theme is configured in the following files:

- `Markdown.sublime-settings`
- `Markdown (Standard).sublime-settings`
- `MultiMarkdown.sublime-settings`

### JSON Key-Value

This highlights strings for keys and values different, so that JSON files are easier to read. Again, it lives at `~/Library/Application Support/Sublime Text 3/Packages/User/JSON Key-Value.sublime-settings`.
