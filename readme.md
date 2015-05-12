# Atom-Package

This is the list of packages for my atom config

## packages
* minimap : https://atom.io/packages/minimap
* linter : https://atom.io/users/AtomLinter
* linter-jshint : https://atom.io/packages/linter-jshint
* atom-beautify : https://atom.io/packages/atom-beautify
* file-icons : https://atom.io/packages/file-icons
* escape-utils : https://atom.io/packages/escape-utils
* pretty-json : https://atom.io/packages/pretty-json


* linter-tidy : https://atom.io/packages/linter-tidy
* linter-ccslint : https://atom.io/packages/linter-csslint
* linter-javac :  https://atom.io/packages/linter-javac
* linter-scalac :  https://atom.io/packages/linter-scalac
* language-scala : https://atom.io/packages/language-scala
* linter-shellcheck : https://atom.io/packages/linter-shellcheck
* linter-jsonlint : https://atom.io/packages/linter-jsonlint
* atom-terminal : https://atom.io/packages/atom-terminal
* git-log : https://atom.io/packages/git-log
* grunt-runner : https://atom.io/packages/grunt-runner
* view-tail-large-files : https://atom.io/packages/view-tail-large-files
* git-control : https://atom.io/packages/git-control
* gist-it : https://atom.io/packages/gist-it
* merge-conflicts : https://atom.io/packages/merge-conflicts
* minimap-find-and-replace : https://atom.io/packages/minimap-find-and-replace
* todo-show : https://atom.io/packages/todo-show
* highlight-selected  https://atom.io/packages/highlight-selected
* minimap-highlight-selected : https://atom.io/packages/minimap-highlight-selected
* open-recent : https://atom.io/packages/open-recent

## theme
* Monokai : https://atom.io/themes/monokai

## misc config
* azerty keybord (windows)
update keybinding to allow the key for ``]`` in both files:
- `c:\Users\USER\.atom\keymap.cson`
- `c:\Users\USER\AppData\Local\atom\VERSION\resources\app\keymaps\win32.json`

```
'atom-workspace atom-text-editor:not([mini])':
  'ctrl-alt-[': 'unset!'
```

* file-icons:

open config files :

`_icons.less` or `icons.less`
```
  .geojson-icon { .fa; content: "\f0ac"; }
```

`_file-icons.less` or `file-icons.less`

```
   &[data-name$=".geojson"]:before { .geojson-icon; .medium-yellow; }
```
