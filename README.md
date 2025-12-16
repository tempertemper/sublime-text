# Sublime text custom config

Somewhere to keep a record of my Sublime Text preferences and list the packages I install.


## Packages

These are all installed via Package Control unless otherwise stated. If you don't already have it [Package Control itself should be installed](https://packagecontrol.io/installation) before going any further.

- [EditorConfig](https://packagecontrol.io/packages/EditorConfig)
- [JSON Key-Value](https://packagecontrol.io/packages/JSON%20Key-Value)
- [MarkdownEditing](https://sublimetext-markdown.github.io/MarkdownEditing/)
- [Nunjucks](https://github.com/alsolovyev/Nunjucks)
- [Package Control](https://packagecontrol.io)
- [Project Specific Syntax Settings](https://github.com/reywood/sublime-project-specific-syntax)
- [Sass](https://packagecontrol.io/packages/Sass)
- [Monokai Pro](https://github.com/monokai-pro/sublime-text)
- [TOML](https://packagecontrol.io/packages/TOML)


## Preferences, etc.

For preferences, see `Preferences.sublime-settings` in this repo, located at `~/Library/Application Support/Sublime Text 3/Packages/User/`

For keybindings, see `Default (OSX).sublime-keymap` in this repo, located at `~/Library/Application Support/Sublime Text 3/Packages/User/`


## Package config

Many of these packages have their own configuration. The config files are in this repo and should be added to `~/Library/Application Support/Sublime Text 3/Packages/User/`.


### MarkdownEditing

Bold and italic markers are `_` and `__` by default. This should be overridden to `*` and `**` in `Bold and Italic Markers.tmPreferences` (file in this repo), which should live in `~/Library/Application Support/Sublime Text 3/Packages/User/Bold and Italic Markers.tmPreferences`

The editor theme is configured in the following files:

- `Markdown.sublime-settings`
- `Markdown (Standard).sublime-settings`
- `MultiMarkdown.sublime-settings`

