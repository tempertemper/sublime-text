# Sublime text custom config

Somewhere to keep a record of my Sublime Text preferences and list the packages I install.

## Packages

+ ApacheConf
+ Bump
+ Color Highlighter
+ EditorConfig
+ Emmet
+ Handlebars
+ MarkdownEditiing
+ nginx
+ nunjucks-extended (install [directly from repo](https://github.com/thecodechef/nunjucks-extended))
+ One Dark Color Scheme
+ Package Control
+ ProjectManager
+ PyV8
+ Sass
+ SublimeLinter-contrib-scss-lint
+ Theme - Spacegray
+ TypeScript

## Preferences, etc.

For preferences, see `Preferences.sublime-settings` in this repo, located at `~/Library/Application Support/Sublime Text 3/Packages/User/Preferences.sublime-settings`

For keybindings, see `Default (OSX).sublime-keymap` in this repo, located at `~/Library/Application Support/Sublime Text 3/Packages/User/Default (OSX).sublime-keymap`


## Package config

### Color Highlighter

If not already installed, run `brew install ImageMagick`, which gets the gutter icons working. From the (annoying) series of dropdown menus, choose the following:

+ Tools → Color Highlighter → Color Highlighters → Highlight colors in selected text → Inline highlighting style → Filled
+ Tools → Color Highlighter → Color Highlighters → Highlight colors in all text → Inline highlighting style → Text
+ Tools → Color Highlighter → Color Highlighters → Highlight colors in all text → Gutter icon style → Circle

All the rest should be 'None'.

See `ColorHighlighter.sublime-settings` file in this repo, which should live in `~/Library/Application Support/Sublime Text 3/Packages/User/ColorHighlighter.sublime-settings`

### MarkdownEditing

Bold and italic markers are `_` and `__` by default. This should be overriden to `*` and `**` in `Bold and Italic Markers.tmPreferences` (file in this repo), which should live in `~/Library/Application Support/Sublime Text 3/Packages/User/Bold and Italic Markers.tmPreferences`

The editor theme should be set to ArkDark, via the `Markdown.sublime-settings` file in `~/Library/Application Support/Sublime Text 3/Packages/User/Markdown.sublime-settings`
