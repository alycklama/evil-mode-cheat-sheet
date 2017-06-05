- [General](#orgb094ca4)
- [Prefix commands](#orged721a7)
- [Selection](#org521c12c)
- [Navigation](#org250b2bd)
- [Searching / Finding](#org9cbf497)
- [Editing](#org106c135)
- [Navigation](#orgbc2afac)
- [Window management](#org4d6004f)
- [Bindings starting with g](#org0362235)
- [Macro](#org0d762a6)
- [Other](#orgacac374)


<a id="orgb094ca4"></a>

# General

| Shortcut | Binding                      |
|-------- |---------------------------- |
| C-r      | redo                         |
| u        | undo                         |
| y        | evil-yank                    |
| Y        | evil-yank-line               |
| .        | evil-repeat                  |
| p        | evil-paste-after             |
| P        | evil-paste-before            |
| TAB      | evil-jump-forward            |
| C-o      | evil-jump-backward           |
| %        | evil-jump-item               |
| C-p      | evil-paste-pop               |
| C-n      | evil-paste-pop-next          |
| C-t      | pop-tag-mark                 |
| Z Q      | evil-quit                    |
| Z Z      | evil-save-modified-and-close |


<a id="orged721a7"></a>

# Prefix commands

| Shortcut | Binding        |
|-------- |-------------- |
| ESC      | Prefix Command |
| Z        | Prefix Command |
| g        | Prefix Command |
| z        | Prefix Command |
| [        | Prefix Command |
| ]        | Prefix Command |


<a id="org521c12c"></a>

# Selection

| Shortcut | Binding             | Description                 |
|-------- |------------------- |--------------------------- |
| g v      | evil-visual-restore | Restore previous selection. |
| V        | evil-visual-line    | Linewise selection          |
| v        | evil-visual-char    | Characterwise selection     |
| C-v      | evil-visual-block   | Blockwise selection         |


<a id="org250b2bd"></a>

# Navigation

| Shortcut | Binding                                       | Description                                                                  |
|-------- |--------------------------------------------- |---------------------------------------------------------------------------- |
| RET      | evil-ret                                      |                                                                              |
| '        | evil-goto-mark-line                           |                                                                              |
| \`       | evil-goto-mark                                |                                                                              |
| &vert;   | evil-goto-column                              |                                                                              |
| o        | evil-open-below                               |                                                                              |
| O        | evil-open-above                               |                                                                              |
| H        | evil-window-top                               |                                                                              |
| M        | evil-window-middle                            |                                                                              |
| L        | evil-window-bottom                            |                                                                              |
| C-y      | evil-scroll-line-up                           |                                                                              |
| C-e      | evil-scroll-line-down                         |                                                                              |
| C-b      | evil-scroll-page-up                           |                                                                              |
| C-f      | evil-scroll-page-down                         |                                                                              |
| C-d      | evil-scroll-down                              |                                                                              |
| z t      | evil-scroll-line-to-top                       |                                                                              |
| z z      | evil-scroll-line-to-center                    |                                                                              |
| z b      | evil-scroll-line-to-bottom                    |                                                                              |
| z ^      | evil-scroll-top-line-to-bottom                |                                                                              |
| z +      | evil-scroll-bottom-line-to-top                |                                                                              |
| z H      | evil-scroll-left                              |                                                                              |
| z L      | evil-scroll-right                             |                                                                              |
| z h      | evil-scroll-column-left                       |                                                                              |
| z l      | evil-scroll-column-right                      |                                                                              |
| z O      | evil-open-fold-rec                            |                                                                              |
| z a      | evil-toggle-fold                              |                                                                              |
| z o      | evil-open-fold                                |                                                                              |
| z c      | evil-close-fold                               |                                                                              |
| z r      | evil-open-folds                               |                                                                              |
| z m      | evil-close-folds                              |                                                                              |
| C-w      | evil-window-map                               |                                                                              |
| C-z      | evil-emacs-state                              |                                                                              |
| C-]      | evil-jump-to-tag                              |                                                                              |
| C-^      | evil-buffer                                   |                                                                              |
| <up>     | evil-previous-visual-line                     |                                                                              |
| <down>   | evil-next-visual-line                         |                                                                              |
| <left>   | evil-backward-char                            |                                                                              |
| <right>  | evil-forward-char                             |                                                                              |
| SPC      | evil-forward-char                             |                                                                              |
| j        | evil-next-visual-line                         |                                                                              |
| k        | evil-previous-visual-line                     |                                                                              |
| g j      | evil-next-visual-line                         |                                                                              |
| g k      | evil-previous-visual-line                     |                                                                              |
| g 0      | evil-beginning-of-visual-line                 |                                                                              |
| g $      | evil-end-of-visual-line                       |                                                                              |
| w        | evil-forward-word-begin                       |                                                                              |
| W        | evil-forward-WORD-begin                       |                                                                              |
| e        | evil-forward-word-end                         |                                                                              |
| E        | evil-forward-WORD-end                         |                                                                              |
| b        | evil-backward-word-begin                      |                                                                              |
| B        | evil-backward-WORD-begin                      |                                                                              |
| g e      | evil-backward-word-end                        |                                                                              |
| g E      | evil-backward-WORD-end                        |                                                                              |
| g g      | evil-goto-first-line                          |                                                                              |
| G        | evil-goto-line                                | Go to the first non-blank character of line COUNT. By default the last line. |
| g m      | evil-middle-of-visual-line                    |                                                                              |
| g ,      | goto-last-change-reverse                      |                                                                              |
| g ;      | goto-last-change                              |                                                                              |
| g d      | evil-goto-definition                          |                                                                              |
| $        | evil-end-of-line                              |                                                                              |
| )        | evil-forward-sentence-begin                   |                                                                              |
| (        | evil-backward-sentence-begin                  |                                                                              |
| +        | evil-next-line-first-non-blank                |                                                                              |
| ^        | evil-first-non-blank                          |                                                                              |
| \_       | evil-next-line-1-first-non-blank              |                                                                              |
| g \_     | evil-last-non-blank                           |                                                                              |
| 0        | evil-digit-argument-or-evil-beginning-of-line |                                                                              |
| g ^      | evil-first-non-blank-of-visual-line           |                                                                              |
| h        | evil-backward-char                            |                                                                              |
| l        | evil-forward-char                             |                                                                              |
| [ (      | evil-previous-open-paren                      |                                                                              |
| [ [      | evil-backward-section-begin                   |                                                                              |
| [ ]      | evil-backward-section-end                     |                                                                              |
| [ s      | evil-prev-flyspell-error                      |                                                                              |
| [ {      | evil-previous-open-brace                      |                                                                              |
| ] )      | evil-next-close-paren                         |                                                                              |
| ] [      | evil-forward-section-end                      |                                                                              |
| ] ]      | evil-forward-section-begin                    |                                                                              |
| ] s      | evil-next-flyspell-error                      |                                                                              |
| ] }      | evil-next-close-brace                         |                                                                              |


<a id="org9cbf497"></a>

# Searching / Finding

| Shortcut | Binding                             |
|-------- |----------------------------------- |
| #        | evil-search-word-backward           |
| \*       | evil-search-word-forward            |
| ?        | evil-search-backward                |
| N        | evil-search-previous                |
| n        | evil-search-next                    |
| g #      | evil-search-unbounded-word-backward |
| g \*     | evil-search-unbounded-word-forward  |
| g N      | evil-previous-match                 |
| g n      | evil-next-match                     |
| ,        | evil-repeat-find-char-reverse       |
| ;        | evil-repeat-find-char               |
| F        | evil-find-char-backward             |
| T        | evil-find-char-to-backward          |
| f        | evil-find-char                      |
| t        | evil-find-char-to                   |
| g f      | find-file-at-point                  |
| g F      | evil-find-file-at-point-with-line   |
| g C-]    | find-tag                            |


<a id="org106c135"></a>

# Editing

| Shortcut | Binding                   |                                                                                                                                                                                                                     |
|-------- |------------------------- |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <        | evil-shift-left           |                                                                                                                                                                                                                     |
| =        | evil-indent               |                                                                                                                                                                                                                     |
| >        | evil-shift-right          |                                                                                                                                                                                                                     |
| A        | evil-append-line          |                                                                                                                                                                                                                     |
| C        | evil-change-line          |                                                                                                                                                                                                                     |
| D        | evil-delete-line          |                                                                                                                                                                                                                     |
| I        | evil-insert-line          |                                                                                                                                                                                                                     |
| S        | evil-change-whole-line    |                                                                                                                                                                                                                     |
| X        | evil-delete-backward-char |                                                                                                                                                                                                                     |
| J        | evil-join                 |                                                                                                                                                                                                                     |
| R        | evil-replace-state        |                                                                                                                                                                                                                     |
| a        | evil-append               |                                                                                                                                                                                                                     |
| c        | evil-change               |                                                                                                                                                                                                                     |
| d        | evil-delete               |                                                                                                                                                                                                                     |
| i        | evil-insert               |                                                                                                                                                                                                                     |
| x        | evil-delete-char          |                                                                                                                                                                                                                     |
| g J      | evil-join-whitespace      |                                                                                                                                                                                                                     |
| g U      | evil-upcase               |                                                                                                                                                                                                                     |
| g u      | evil-downcase             |                                                                                                                                                                                                                     |
| g ~      | evil-invert-case          |                                                                                                                                                                                                                     |
| g ?      | evil-rot13                | ROT13 encrypt text.                                                                                                                                                                                                 |
| g i      | evil-insert-resume        | Switch to Insert state at previous insertion point. The insertion will be repeated COUNT times. If called from visual state, only place point at the previous insertion position but do not switch to insert state. |
| g q      | evil-fill-and-move        |                                                                                                                                                                                                                     |
| g w      | evil-fill                 | Fill text.                                                                                                                                                                                                          |


<a id="orgbc2afac"></a>

# Navigation

| Shortcut       | Binding                            | Description |
|-------------- |---------------------------------- |----------- |
| !              | evil-shell-command                 |             |
| 1 .. 9         | digit-argument                     |             |
| K              | evil-lookup                        |             |
| \\             | evil-execute-in-emacs-state        |             |
| }              | evil-forward-paragraph             |             |
| {              | evil-backward-paragraph            |             |
| C-6            | evil-switch-to-windows-last-buffer |             |
| <down-mouse-1> | evil-mouse-drag-region             |             |


<a id="org4d6004f"></a>

# Window management

| Shortcut   | Binding                      | Description                                                                                                                                                                                                                                    |
|---------- |---------------------------- |---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| C-w C-n    | evil-window-new              |                                                                                                                                                                                                                                                |
| C-w n      | evil-window-new              |                                                                                                                                                                                                                                                |
| C-w C-c    | evil-window-delete           |                                                                                                                                                                                                                                                |
| C-w c      | evil-window-delete           |                                                                                                                                                                                                                                                |
| C-w C-o    | delete-other-windows         |                                                                                                                                                                                                                                                |
| C-w o      | delete-other-windows         |                                                                                                                                                                                                                                                |
| C-w k      | evil-window-up               |                                                                                                                                                                                                                                                |
| C-w j      | evil-window-down             |                                                                                                                                                                                                                                                |
| C-w h      | evil-window-left             |                                                                                                                                                                                                                                                |
| C-w l      | evil-window-right            |                                                                                                                                                                                                                                                |
| C-w t      | evil-window-top-left         |                                                                                                                                                                                                                                                |
| C-w C-t    | evil-window-top-left         |                                                                                                                                                                                                                                                |
| C-w b      | evil-window-bottom-right     |                                                                                                                                                                                                                                                |
| C-w C-b    | evil-window-bottom-right     |                                                                                                                                                                                                                                                |
| C-w C-f    | ffap-other-window            | Like ‘ffap’, but put buffer in another window. Only intended for interactive use.                                                                                                                                                              |
| C-w =      | balance-windows              |                                                                                                                                                                                                                                                |
| -w C-s     | evil-window-split            |                                                                                                                                                                                                                                                |
| C-w s      | evil-window-split            |                                                                                                                                                                                                                                                |
| C-w C-S-s  | evil-window-split            |                                                                                                                                                                                                                                                |
| C-w v      | evil-window-vsplit           |                                                                                                                                                                                                                                                |
| C-w C-v    | evil-window-vsplit           |                                                                                                                                                                                                                                                |
| C-w S      | evil-window-split            |                                                                                                                                                                                                                                                |
| C-w R      | evil-window-rotate-upwards   |                                                                                                                                                                                                                                                |
| C-w r      | evil-window-rotate-downwards |                                                                                                                                                                                                                                                |
| C-w C-S-r  | evil-window-rotate-upwards   |                                                                                                                                                                                                                                                |
| C-w C-r    | evil-window-rotate-downwards |                                                                                                                                                                                                                                                |
| C-w C-\_   | evil-window-set-height       |                                                                                                                                                                                                                                                |
| C-w \_     | evil-window-set-height       |                                                                                                                                                                                                                                                |
| C-w &vert; | evil-window-set-width        |                                                                                                                                                                                                                                                |
| C-w +      | evil-window-increase-height  |                                                                                                                                                                                                                                                |
| C-w -      | evil-window-decrease-height  |                                                                                                                                                                                                                                                |
| C-w >      | evil-window-increase-width   |                                                                                                                                                                                                                                                |
| C-w <      | evil-window-decrease-width   |                                                                                                                                                                                                                                                |
| C-w w      | evil-window-next             |                                                                                                                                                                                                                                                |
| C-w C-w    | evil-window-next             |                                                                                                                                                                                                                                                |
| C-w W      | evil-window-prev             |                                                                                                                                                                                                                                                |
| C-w C-S-w  | evil-window-prev             |                                                                                                                                                                                                                                                |
| C-w C-p    | evil-window-mru              | Move the cursor to the previous (last accessed) buffer in another window. More precisely, it selects the most recently used buffer that is shown in some other window, preferably of the current frame, and is different from the current one. |
| C-w p      | evil-window-mru              |                                                                                                                                                                                                                                                |
| C-w K      | evil-window-move-very-top    |                                                                                                                                                                                                                                                |
| C-w C-S-k  | evil-window-move-very-top    |                                                                                                                                                                                                                                                |
| C-w J      | evil-window-move-very-bottom |                                                                                                                                                                                                                                                |
| C-w C-S-j  | evil-window-move-very-bottom |                                                                                                                                                                                                                                                |
| C-w H      | evil-window-move-far-left    |                                                                                                                                                                                                                                                |
| C-w C-S-h  | evil-window-move-far-left    |                                                                                                                                                                                                                                                |
| C-w L      | evil-window-move-far-right   |                                                                                                                                                                                                                                                |
| C-w C-S-l  | evil-window-move-far-right   |                                                                                                                                                                                                                                                |


<a id="org0362235"></a>

# Bindings starting with g

| Shortcut | Binding              | Description |
|-------- |-------------------- |----------- |
| g 8      | what-cursor-position |             |
| g a      | what-cursor-position |             |


<a id="org0d762a6"></a>

# Macro

| Shortcut   | Binding            |
|---------- |------------------ |
| @          | evil-execute-macro |
| q          | evil-record-macro  |
| z RET      | Keyboard Macro     |
| z -        | Keyboard Macro     |
| z .        | Keyboard Macro     |
| z <left>   | Keyboard Macro     |
| z <return> | Keyboard Macro     |
| z <right>  | Keyboard Macro     |


<a id="orgacac374"></a>

# Other

| Shortcut | Binding                          |
|-------- |-------------------------------- |
| "        | evil-use-register                |
| m        | evil-set-marker                  |
| r        | evil-replace                     |
| s        | evil-substitute                  |
| ~        | evil-invert-char                 |
| DEL      | evil-backward-char               |
| C-.      | evil-repeat-pop                  |
| M-.      | evil-repeat-pop-next             |
| :        | evil-ex                          |
| &        | evil-ex-repeat-substitute        |
| g &      | evil-ex-repeat-global-substitute |