# Zend For Linux
## Custom Keymap
`ctrl-k ctrl-s` open zed keymap
```json
[
  {
    "context": "VimControl && !menu",
    "bindings": {
      "ctrl-j": "workspace::ToggleBottomDock"
    }
  }
]
```

## Global
* `shift-esc` Toggle zoom
* `ctrl-shift-F` find in project
* `G space` find in project open file
* `ctrl-alt-Y` Close all docks
* `ctrl-J` Toggle Terminal
* `ctrl-B` Toggle Explorer
* `ctrl-alt-B` CoPilot Chat

## Explorer
* `ctrl-shift-E` to jump between the file tree
* `shift-D` delete
### Outline
* `shift-b` Outline

## Editor
### Visual Mode
* `G T` to go to the next tab.
* `G shift-T` to go to the previous tab.
* `ctrl-tab` switch between tabs in list
* `ctrl-W O` Close other Tabs
* `shift-z shift-q` Close Tab without saving
* `shift-z shift-z` Close Tab with saving
* `ctrl-backtick` Open or move to terminal
### Insert Mode
* `ctrl-x ctrl-a` copilot
* `ctrl-n` Context Menu Next
* `ctrl-p` Context Menu Prev
### Windows Split
* `ctrl-W H` to move to the left split.
* `ctrl-W J` to move to the split below.
* `ctrl-W K` to move to the split above.
* `ctrl-W L` to move to the right split.
### Context Menu
* `ctrl-space` autocompletion list

## Terminal
* `ctrl-tab` switch between tabs in list
* `ctrl-backtick` move to editor
* `ctrl-~` new tab
* `ctrl-enter` AI
* `ctrl-shift-f` search
* `shift-pageup` scroll up
* `shift-pagedown` scroll down
* `shift-end` scroll bottom
* `ctrl-J` collapse

## Sources
1. https://zed.dev/docs/key-bindings#all-key-bindings
2. https://github.com/zed-industries/zed/blob/main/assets/keymaps/vim.json
3. https://zed.dev/docs/vim
4. https://zed.dev/features
