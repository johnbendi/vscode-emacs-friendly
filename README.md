# vscode-emacs

This is emacs like plugin for Visual Studio Code.

## Operation

### Move command
|Command | Status | Desc |
|--------|--------|------|
| C-f | OK | Move to the forward |
| C-b | OK | Move to the backward |
| C-n | OK | Move to the next line |
| C-p | OK | Move to the previous line |
| C-a | OK | Move to the beginning of line |
| C-e | OK | Move to the end of line |
| M-f | OK | Move to the forward by one word unit |
| M-b | OK | Move to the backward by one word unit |
| C-v | OK | Scroll down by one screen unit |
| M-v | OK | Scroll up by one screen unit |
| M-> | OK | Move to the end of buffer |
| M-< | OK | Move to the beginning of buffer |
| M-r | - | - |
| M-x goto-line | - | Jump to line |
| M-x goto-char | - | - |
| C-x C-n | - | - |
| C-u C-x C-n | - |deactivate C-x C-n |
| M-g g | △ | Jump to line (command palette) |


### Search Command
|Command | Status | Desc |
|--------|--------|------|
| C-s | - | - |
| C-r | - | - |
| C-l | - | - |
| M-x (regex) | - | - |
| M-% (string) | - | - |

### Edit command
|Command | Status | Desc |
|--------|--------|------|
| C-d | OK | Delete right from point (DEL)|
| C-h | OK | Delete left from point (BS) |
| M-d | OK | Delete word at current position |
| C-k | OK | Delete character from current point to line end |
| C-w | OK | Delete region |
| M-w | OK | Copy region |
| C-y | OK | Past region |
| C-j | OK | Return (Enter) |
| C-m | OK | Return (Enter) |
| C-o | OK | Insert blank to next line (open-line) |
| C-x C-o | - | - |
| C-x h | - | - |
| C-x u | OK | Undo |
| C-x z | - | Redo |
| M-x tabify | - | - |
| M-x untabify | - | - |
| M-x comment-region | - | Comment out |
| C-u M-x comment-region | - | Comment in |
| C-; | OK | Toggle line comment in and out |
| M-; | OK | Toggle region comment in and out |
| C-m-\ (C-:) | - | Auto indent |

### Command
|Command | Status | Desc |
|--------|--------|------|
| C-g | △ | Cancel |
| C-space | OK | Set mark |
| C-\ | - | IME control |

### File Command
|Command | Status | Desc |
|--------|--------|------|
| C-x C-f | OK | Open |
| C-x C-s | OK | Save |
| C-x C-w | OK | Save as |
| C-x i | - | Insert buffer from file |
| C-x C-d | - | Open Folder |
| C-x C-n | - | Open new window |
| C-x C-b | - | Create new file and open |


### Other
|Command | Status | Desc |
|--------|--------|------|
| Esc-x shell | - | Start up to the shell |
| M-/(dabbrev)| - | - |
| M-num command | - | - |
