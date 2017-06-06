- [Intro](#org134781e)
- [General](#orga152074)
- [Prefix commands](#org67f593f)
- [Selection](#org4d8b410)
- [Navigation](#org118cc9e)
- [Searching / Finding](#org3523663)
- [Editing](#orgdb04521)
- [Navigation](#org2d963af)
- [Window management](#orge082ee4)
- [Bindings starting with g](#org14783d2)
- [Macro](#org4e087ff)
- [Other](#orgc32ae54)


<a id="org134781e"></a>

# Intro

This is a cheat&nbsp;sheet for evil&nbsp;mode. There are so many key&nbsp;bindings that I took the opportunity to create a handy cheat&nbsp;sheet, supporting my own learning process. If anything is missing or wrong, pull requests are more than welcome!


<a id="orga152074"></a>

# General

| Shortcut | Binding                                          |
|-------- |------------------------------------------------ |
| C&nbsp;r | redo                                             |
| u        | undo                                             |
| y        | evil&nbsp;yank                                   |
| Y        | evil&nbsp;yank&nbsp;line                         |
| .        | evil&nbsp;repeat                                 |
| p        | evil&nbsp;paste&nbsp;after                       |
| P        | evil&nbsp;paste&nbsp;before                      |
| TAB      | evil&nbsp;jump&nbsp;forward                      |
| C&nbsp;o | evil&nbsp;jump&nbsp;backward                     |
| %        | evil&nbsp;jump&nbsp;item                         |
| C&nbsp;p | evil&nbsp;paste&nbsp;pop                         |
| C&nbsp;n | evil&nbsp;paste&nbsp;pop&nbsp;next               |
| C&nbsp;t | pop&nbsp;tag&nbsp;mark                           |
| Z Q      | evil&nbsp;quit                                   |
| Z Z      | evil&nbsp;save&nbsp;modified&nbsp;and&nbsp;close |


<a id="org67f593f"></a>

# Prefix commands

| Shortcut | Binding        |
|-------- |-------------- |
| ESC      | Prefix Command |
| Z        | Prefix Command |
| g        | Prefix Command |
| z        | Prefix Command |
| [        | Prefix Command |
| ]        | Prefix Command |


<a id="org4d8b410"></a>

# Selection

| Shortcut | Binding                       | Description                 |
|-------- |----------------------------- |--------------------------- |
| g v      | evil&nbsp;visual&nbsp;restore | Restore previous selection. |
| V        | evil&nbsp;visual&nbsp;line    | Linewise selection          |
| v        | evil&nbsp;visual&nbsp;char    | Characterwise selection     |
| C&nbsp;v | evil&nbsp;visual&nbsp;block   | Blockwise selection         |


<a id="org118cc9e"></a>

# Navigation

| Shortcut        | Binding                                                                          | Description                                                                       |
|--------------- |-------------------------------------------------------------------------------- |--------------------------------------------------------------------------------- |
| RET             | evil&nbsp;ret                                                                    |                                                                                   |
| '               | evil&nbsp;goto&nbsp;mark&nbsp;line                                               |                                                                                   |
| \`              | evil&nbsp;goto&nbsp;mark                                                         |                                                                                   |
| &vert;          | evil&nbsp;goto&nbsp;column                                                       |                                                                                   |
| o               | evil&nbsp;open&nbsp;below                                                        |                                                                                   |
| O               | evil&nbsp;open&nbsp;above                                                        |                                                                                   |
| H               | evil&nbsp;window&nbsp;top                                                        |                                                                                   |
| M               | evil&nbsp;window&nbsp;middle                                                     |                                                                                   |
| L               | evil&nbsp;window&nbsp;bottom                                                     |                                                                                   |
| C&nbsp;y        | evil&nbsp;scroll&nbsp;line&nbsp;up                                               |                                                                                   |
| C&nbsp;e        | evil&nbsp;scroll&nbsp;line&nbsp;down                                             |                                                                                   |
| C&nbsp;b        | evil&nbsp;scroll&nbsp;page&nbsp;up                                               |                                                                                   |
| C&nbsp;f        | evil&nbsp;scroll&nbsp;page&nbsp;down                                             |                                                                                   |
| C&nbsp;d        | evil&nbsp;scroll&nbsp;down                                                       |                                                                                   |
| z t             | evil&nbsp;scroll&nbsp;line&nbsp;to&nbsp;top                                      |                                                                                   |
| z z             | evil&nbsp;scroll&nbsp;line&nbsp;to&nbsp;center                                   |                                                                                   |
| z b             | evil&nbsp;scroll&nbsp;line&nbsp;to&nbsp;bottom                                   |                                                                                   |
| z ^             | evil&nbsp;scroll&nbsp;top&nbsp;line&nbsp;to&nbsp;bottom                          |                                                                                   |
| z +             | evil&nbsp;scroll&nbsp;bottom&nbsp;line&nbsp;to&nbsp;top                          |                                                                                   |
| z H             | evil&nbsp;scroll&nbsp;left                                                       |                                                                                   |
| z L             | evil&nbsp;scroll&nbsp;right                                                      |                                                                                   |
| z h             | evil&nbsp;scroll&nbsp;column&nbsp;left                                           |                                                                                   |
| z l             | evil&nbsp;scroll&nbsp;column&nbsp;right                                          |                                                                                   |
| z O             | evil&nbsp;open&nbsp;fold&nbsp;rec                                                |                                                                                   |
| z a             | evil&nbsp;toggle&nbsp;fold                                                       |                                                                                   |
| z o             | evil&nbsp;open&nbsp;fold                                                         |                                                                                   |
| z c             | evil&nbsp;close&nbsp;fold                                                        |                                                                                   |
| z r             | evil&nbsp;open&nbsp;folds                                                        |                                                                                   |
| z m             | evil&nbsp;close&nbsp;folds                                                       |                                                                                   |
| C&nbsp;w        | evil&nbsp;window&nbsp;map                                                        |                                                                                   |
| C&nbsp;z        | evil&nbsp;emacs&nbsp;state                                                       |                                                                                   |
| C-]             | evil&nbsp;jump&nbsp;to&nbsp;tag                                                  |                                                                                   |
| C-^             | evil&nbsp;buffer                                                                 |                                                                                   |
| &#60;up&#62;    | evil&nbsp;previous&nbsp;visual&nbsp;line                                         |                                                                                   |
| &#60;down&#62;  | evil&nbsp;next&nbsp;visual&nbsp;line                                             |                                                                                   |
| &#60;left&#62;  | evil&nbsp;backward&nbsp;char                                                     |                                                                                   |
| &#60;right&#62; | evil&nbsp;forward&nbsp;char                                                      |                                                                                   |
| SPC             | evil&nbsp;forward&nbsp;char                                                      |                                                                                   |
| j               | evil&nbsp;next&nbsp;visual&nbsp;line                                             |                                                                                   |
| k               | evil&nbsp;previous&nbsp;visual&nbsp;line                                         |                                                                                   |
| g j             | evil&nbsp;next&nbsp;visual&nbsp;line                                             |                                                                                   |
| g k             | evil&nbsp;previous&nbsp;visual&nbsp;line                                         |                                                                                   |
| g 0             | evil&nbsp;beginning&nbsp;of&nbsp;visual&nbsp;line                                |                                                                                   |
| g $             | evil&nbsp;end&nbsp;of&nbsp;visual&nbsp;line                                      |                                                                                   |
| w               | evil&nbsp;forward&nbsp;word&nbsp;begin                                           |                                                                                   |
| W               | evil&nbsp;forward&nbsp;WORD&nbsp;begin                                           |                                                                                   |
| e               | evil&nbsp;forward&nbsp;word&nbsp;end                                             |                                                                                   |
| E               | evil&nbsp;forward&nbsp;WORD&nbsp;end                                             |                                                                                   |
| b               | evil&nbsp;backward&nbsp;word&nbsp;begin                                          |                                                                                   |
| B               | evil&nbsp;backward&nbsp;WORD&nbsp;begin                                          |                                                                                   |
| g e             | evil&nbsp;backward&nbsp;word&nbsp;end                                            |                                                                                   |
| g E             | evil&nbsp;backward&nbsp;WORD&nbsp;end                                            |                                                                                   |
| g g             | evil&nbsp;goto&nbsp;first&nbsp;line                                              |                                                                                   |
| G               | evil&nbsp;goto&nbsp;line                                                         | Go to the first non&nbsp;blank character of line COUNT. By default the last line. |
| g m             | evil&nbsp;middle&nbsp;of&nbsp;visual&nbsp;line                                   |                                                                                   |
| g ,             | goto&nbsp;last&nbsp;change&nbsp;reverse                                          |                                                                                   |
| g ;             | goto&nbsp;last&nbsp;change                                                       |                                                                                   |
| g d             | evil&nbsp;goto&nbsp;definition                                                   |                                                                                   |
| $               | evil&nbsp;end&nbsp;of&nbsp;line                                                  |                                                                                   |
| )               | evil&nbsp;forward&nbsp;sentence&nbsp;begin                                       |                                                                                   |
| (               | evil&nbsp;backward&nbsp;sentence&nbsp;begin                                      |                                                                                   |
| +               | evil&nbsp;next&nbsp;line&nbsp;first&nbsp;non&nbsp;blank                          |                                                                                   |
| ^               | evil&nbsp;first&nbsp;non&nbsp;blank                                              |                                                                                   |
| \_              | evil&nbsp;next&nbsp;line-1-first&nbsp;non&nbsp;blank                             |                                                                                   |
| g \_            | evil&nbsp;last&nbsp;non&nbsp;blank                                               |                                                                                   |
| 0               | evil&nbsp;digit&nbsp;argument&nbsp;or&nbsp;evil&nbsp;beginning&nbsp;of&nbsp;line |                                                                                   |
| g ^             | evil&nbsp;first&nbsp;non&nbsp;blank&nbsp;of&nbsp;visual&nbsp;line                |                                                                                   |
| h               | evil&nbsp;backward&nbsp;char                                                     |                                                                                   |
| l               | evil&nbsp;forward&nbsp;char                                                      |                                                                                   |
| [ (             | evil&nbsp;previous&nbsp;open&nbsp;paren                                          |                                                                                   |
| [ [             | evil&nbsp;backward&nbsp;section&nbsp;begin                                       |                                                                                   |
| [ ]             | evil&nbsp;backward&nbsp;section&nbsp;end                                         |                                                                                   |
| [ s             | evil&nbsp;prev&nbsp;flyspell&nbsp;error                                          |                                                                                   |
| [ {             | evil&nbsp;previous&nbsp;open&nbsp;brace                                          |                                                                                   |
| ] )             | evil&nbsp;next&nbsp;close&nbsp;paren                                             |                                                                                   |
| ] [             | evil&nbsp;forward&nbsp;section&nbsp;end                                          |                                                                                   |
| ] ]             | evil&nbsp;forward&nbsp;section&nbsp;begin                                        |                                                                                   |
| ] s             | evil&nbsp;next&nbsp;flyspell&nbsp;error                                          |                                                                                   |
| ] }             | evil&nbsp;next&nbsp;close&nbsp;brace                                             |                                                                                   |


<a id="org3523663"></a>

# Searching / Finding

| Shortcut | Binding                                                         |
|-------- |--------------------------------------------------------------- |
| #        | evil&nbsp;search&nbsp;word&nbsp;backward                        |
| \*       | evil&nbsp;search&nbsp;word&nbsp;forward                         |
| &#47;    | evil&nbsp;search&nbsp;forward                                   |
| ?        | evil&nbsp;search&nbsp;backward                                  |
| N        | evil&nbsp;search&nbsp;previous                                  |
| n        | evil&nbsp;search&nbsp;next                                      |
| g #      | evil&nbsp;search&nbsp;unbounded&nbsp;word&nbsp;backward         |
| g \*     | evil&nbsp;search&nbsp;unbounded&nbsp;word&nbsp;forward          |
| g N      | evil&nbsp;previous&nbsp;match                                   |
| g n      | evil&nbsp;next&nbsp;match                                       |
| ,        | evil&nbsp;repeat&nbsp;find&nbsp;char&nbsp;reverse               |
| ;        | evil&nbsp;repeat&nbsp;find&nbsp;char                            |
| F        | evil&nbsp;find&nbsp;char&nbsp;backward                          |
| T        | evil&nbsp;find&nbsp;char&nbsp;to&nbsp;backward                  |
| f        | evil&nbsp;find&nbsp;char                                        |
| t        | evil&nbsp;find&nbsp;char&nbsp;to                                |
| g f      | find&nbsp;file&nbsp;at&nbsp;point                               |
| g F      | evil&nbsp;find&nbsp;file&nbsp;at&nbsp;point&nbsp;with&nbsp;line |
| g C-]    | find&nbsp;tag                                                   |


<a id="orgdb04521"></a>

# Editing

| Shortcut | Binding                                  |                                                                                                                                                                                                                     |
|-------- |---------------------------------------- |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| &#60;    | evil&nbsp;shift&nbsp;left                |                                                                                                                                                                                                                     |
| &#61;    | evil&nbsp;indent                         |                                                                                                                                                                                                                     |
| &#62;    | evil&nbsp;shift&nbsp;right               |                                                                                                                                                                                                                     |
| A        | evil&nbsp;append&nbsp;line               |                                                                                                                                                                                                                     |
| C        | evil&nbsp;change&nbsp;line               |                                                                                                                                                                                                                     |
| D        | evil&nbsp;delete&nbsp;line               |                                                                                                                                                                                                                     |
| I        | evil&nbsp;insert&nbsp;line               |                                                                                                                                                                                                                     |
| S        | evil&nbsp;change&nbsp;whole&nbsp;line    |                                                                                                                                                                                                                     |
| X        | evil&nbsp;delete&nbsp;backward&nbsp;char |                                                                                                                                                                                                                     |
| J        | evil&nbsp;join                           |                                                                                                                                                                                                                     |
| R        | evil&nbsp;replace&nbsp;state             |                                                                                                                                                                                                                     |
| a        | evil&nbsp;append                         |                                                                                                                                                                                                                     |
| c        | evil&nbsp;change                         |                                                                                                                                                                                                                     |
| d        | evil&nbsp;delete                         |                                                                                                                                                                                                                     |
| i        | evil&nbsp;insert                         |                                                                                                                                                                                                                     |
| x        | evil&nbsp;delete&nbsp;char               |                                                                                                                                                                                                                     |
| g J      | evil&nbsp;join&nbsp;whitespace           |                                                                                                                                                                                                                     |
| g U      | evil&nbsp;upcase                         |                                                                                                                                                                                                                     |
| g u      | evil&nbsp;downcase                       |                                                                                                                                                                                                                     |
| g ~      | evil&nbsp;invert&nbsp;case               |                                                                                                                                                                                                                     |
| g ?      | evil&nbsp;rot13                          | ROT13 encrypt text.                                                                                                                                                                                                 |
| g i      | evil&nbsp;insert&nbsp;resume             | Switch to Insert state at previous insertion point. The insertion will be repeated COUNT times. If called from visual state, only place point at the previous insertion position but do not switch to insert state. |
| g q      | evil&nbsp;fill&nbsp;and&nbsp;move        |                                                                                                                                                                                                                     |
| g w      | evil&nbsp;fill                           | Fill text.                                                                                                                                                                                                          |


<a id="org2d963af"></a>

# Navigation

| Shortcut                    | Binding                                                     |
|--------------------------- |----------------------------------------------------------- |
| !                           | evil&nbsp;shell&nbsp;command                                |
| 1 .. 9                      | digit&nbsp;argument                                         |
| K                           | evil&nbsp;lookup                                            |
| \\                          | evil&nbsp;execute&nbsp;in&nbsp;emacs&nbsp;state             |
| }                           | evil&nbsp;forward&nbsp;paragraph                            |
| {                           | evil&nbsp;backward&nbsp;paragraph                           |
| C-6                         | evil&nbsp;switch&nbsp;to&nbsp;windows&nbsp;last&nbsp;buffer |
| &#60;down&nbsp;mouse-1&#62; | evil&nbsp;mouse&nbsp;drag&nbsp;region                       |


<a id="orge082ee4"></a>

# Window management

| Shortcut            | Binding                                          | Description                                                                                                                                                                                                                                    |
|------------------- |------------------------------------------------ |---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| C&nbsp;w C&nbsp;n   | evil&nbsp;window&nbsp;new                        |                                                                                                                                                                                                                                                |
| C&nbsp;w n          | evil&nbsp;window&nbsp;new                        |                                                                                                                                                                                                                                                |
| C&nbsp;w C&nbsp;c   | evil&nbsp;window&nbsp;delete                     |                                                                                                                                                                                                                                                |
| C&nbsp;w c          | evil&nbsp;window&nbsp;delete                     |                                                                                                                                                                                                                                                |
| C&nbsp;w C&nbsp;o   | delete&nbsp;other&nbsp;windows                   |                                                                                                                                                                                                                                                |
| C&nbsp;w o          | delete&nbsp;other&nbsp;windows                   |                                                                                                                                                                                                                                                |
| C&nbsp;w k          | evil&nbsp;window&nbsp;up                         |                                                                                                                                                                                                                                                |
| C&nbsp;w j          | evil&nbsp;window&nbsp;down                       |                                                                                                                                                                                                                                                |
| C&nbsp;w h          | evil&nbsp;window&nbsp;left                       |                                                                                                                                                                                                                                                |
| C&nbsp;w l          | evil&nbsp;window&nbsp;right                      |                                                                                                                                                                                                                                                |
| C&nbsp;w t          | evil&nbsp;window&nbsp;top&nbsp;left              |                                                                                                                                                                                                                                                |
| C&nbsp;w C&nbsp;t   | evil&nbsp;window&nbsp;top&nbsp;left              |                                                                                                                                                                                                                                                |
| C&nbsp;w b          | evil&nbsp;window&nbsp;bottom&nbsp;right          |                                                                                                                                                                                                                                                |
| C&nbsp;w C&nbsp;b   | evil&nbsp;window&nbsp;bottom&nbsp;right          |                                                                                                                                                                                                                                                |
| C&nbsp;w C&nbsp;f   | ffap&nbsp;other&nbsp;window                      | Like ‘ffap’, but put buffer in another window. Only intended for interactive use.                                                                                                                                                              |
| C&nbsp;w &#61;      | balance&nbsp;windows                             |                                                                                                                                                                                                                                                |
| -w C&nbsp;s         | evil&nbsp;window&nbsp;split                      |                                                                                                                                                                                                                                                |
| C&nbsp;w s          | evil&nbsp;window&nbsp;split                      |                                                                                                                                                                                                                                                |
| C&nbsp;w C&NBSP;S-s | evil&nbsp;window&nbsp;split                      |                                                                                                                                                                                                                                                |
| C&nbsp;w v          | evil&nbsp;window&nbsp;vsplit                     |                                                                                                                                                                                                                                                |
| C&nbsp;w C&nbsp;v   | evil&nbsp;window&nbsp;vsplit                     |                                                                                                                                                                                                                                                |
| C&nbsp;w S          | evil&nbsp;window&nbsp;split                      |                                                                                                                                                                                                                                                |
| C&nbsp;w R          | evil&nbsp;window&nbsp;rotate&nbsp;upwards        |                                                                                                                                                                                                                                                |
| C&nbsp;w r          | evil&nbsp;window&nbsp;rotate&nbsp;downwards      |                                                                                                                                                                                                                                                |
| C&nbsp;w C&NBSP;S-r | evil&nbsp;window&nbsp;rotate&nbsp;upwards        |                                                                                                                                                                                                                                                |
| C&nbsp;w C&nbsp;r   | evil&nbsp;window&nbsp;rotate&nbsp;downwards      |                                                                                                                                                                                                                                                |
| C&nbsp;w C-\_       | evil&nbsp;window&nbsp;set&nbsp;height            |                                                                                                                                                                                                                                                |
| C&nbsp;w \_         | evil&nbsp;window&nbsp;set&nbsp;height            |                                                                                                                                                                                                                                                |
| C&nbsp;w &vert;     | evil&nbsp;window&nbsp;set&nbsp;width             |                                                                                                                                                                                                                                                |
| C&nbsp;w +          | evil&nbsp;window&nbsp;increase&nbsp;height       |                                                                                                                                                                                                                                                |
| C&nbsp;w -          | evil&nbsp;window&nbsp;decrease&nbsp;height       |                                                                                                                                                                                                                                                |
| C&nbsp;w &#62;      | evil&nbsp;window&nbsp;increase&nbsp;width        |                                                                                                                                                                                                                                                |
| C&nbsp;w &#60;      | evil&nbsp;window&nbsp;decrease&nbsp;width        |                                                                                                                                                                                                                                                |
| C&nbsp;w w          | evil&nbsp;window&nbsp;next                       |                                                                                                                                                                                                                                                |
| C&nbsp;w C&nbsp;w   | evil&nbsp;window&nbsp;next                       |                                                                                                                                                                                                                                                |
| C&nbsp;w W          | evil&nbsp;window&nbsp;prev                       |                                                                                                                                                                                                                                                |
| C&nbsp;w C&NBSP;S-w | evil&nbsp;window&nbsp;prev                       |                                                                                                                                                                                                                                                |
| C&nbsp;w C&nbsp;p   | evil&nbsp;window&nbsp;mru                        | Move the cursor to the previous (last accessed) buffer in another window. More precisely, it selects the most recently used buffer that is shown in some other window, preferably of the current frame, and is different from the current one. |
| C&nbsp;w p          | evil&nbsp;window&nbsp;mru                        |                                                                                                                                                                                                                                                |
| C&nbsp;w K          | evil&nbsp;window&nbsp;move&nbsp;very&nbsp;top    |                                                                                                                                                                                                                                                |
| C&nbsp;w C&NBSP;S-k | evil&nbsp;window&nbsp;move&nbsp;very&nbsp;top    |                                                                                                                                                                                                                                                |
| C&nbsp;w J          | evil&nbsp;window&nbsp;move&nbsp;very&nbsp;bottom |                                                                                                                                                                                                                                                |
| C&nbsp;w C&NBSP;S-j | evil&nbsp;window&nbsp;move&nbsp;very&nbsp;bottom |                                                                                                                                                                                                                                                |
| C&nbsp;w H          | evil&nbsp;window&nbsp;move&nbsp;far&nbsp;left    |                                                                                                                                                                                                                                                |
| C&nbsp;w C&NBSP;S-h | evil&nbsp;window&nbsp;move&nbsp;far&nbsp;left    |                                                                                                                                                                                                                                                |
| C&nbsp;w L          | evil&nbsp;window&nbsp;move&nbsp;far&nbsp;right   |                                                                                                                                                                                                                                                |
| C&nbsp;w C&NBSP;S-l | evil&nbsp;window&nbsp;move&nbsp;far&nbsp;right   |                                                                                                                                                                                                                                                |


<a id="org14783d2"></a>

# Bindings starting with g

| Shortcut | Binding                        |
|-------- |------------------------------ |
| g 8      | what&nbsp;cursor&nbsp;position |
| g a      | what&nbsp;cursor&nbsp;position |


<a id="org4e087ff"></a>

# Macro

| Shortcut           | Binding                      |
|------------------ |---------------------------- |
| @                  | evil&nbsp;execute&nbsp;macro |
| q                  | evil&nbsp;record&nbsp;macro  |
| z RET              | Keyboard Macro               |
| z -                | Keyboard Macro               |
| z .                | Keyboard Macro               |
| z &#60;left&#62;   | Keyboard Macro               |
| z &#60;return&#62; | Keyboard Macro               |
| z &#60;right&#62;  | Keyboard Macro               |


<a id="orgc32ae54"></a>

# Other

| Shortcut | Binding                                              |
|-------- |---------------------------------------------------- |
| "        | evil&nbsp;use&nbsp;register                          |
| m        | evil&nbsp;set&nbsp;marker                            |
| r        | evil&nbsp;replace                                    |
| s        | evil&nbsp;substitute                                 |
| ~        | evil&nbsp;invert&nbsp;char                           |
| DEL      | evil&nbsp;backward&nbsp;char                         |
| C-.      | evil&nbsp;repeat&nbsp;pop                            |
| M-.      | evil&nbsp;repeat&nbsp;pop&nbsp;next                  |
| :        | evil&nbsp;ex                                         |
| &        | evil&nbsp;ex&nbsp;repeat&nbsp;substitute             |
| g &      | evil&nbsp;ex&nbsp;repeat&nbsp;global&nbsp;substitute |