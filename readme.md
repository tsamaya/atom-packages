# Atom-Package

This is the list of packages for my atom config

## packages
* atom-beautify : https://atom.io/packages/atom-beautify
* docblockr : https://atom.io/packages/docblockr
* file-icons : https://atom.io/packages/file-icons
* linter : https://atom.io/users/AtomLinter
* linter-jshint : https://atom.io/packages/linter-jshint
* merge-conflicts : https://atom.io/packages/merge-conflicts
* minimap : https://atom.io/packages/minimap
* pretty-json : https://atom.io/packages/pretty-json

## theme

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
