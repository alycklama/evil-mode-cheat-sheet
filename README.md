- [Intro](#orgace68c7)
- [General](#org25f2de9)
- [Prefix commands](#org269586b)
- [Selection](#org418dc1c)
- [Navigation](#orgd606561)
- [Searching / Finding](#orgc65feeb)
- [Editing](#org586c5ff)
- [Navigation](#orgc80e532)
- [Window management](#org86b1e3e)
- [Bindings starting with g](#orgb129dd2)
- [Macro](#orgd81d16b)
- [Other](#orgf54d111)


<a id="orgace68c7"></a>

# Intro

This is a cheat&nbsp;sheet for evil&nbsp;mode. There are so many key&nbsp;bindings that I took the opportunity to create a handy cheat&nbsp;sheet, supporting my own learning process. If anything is missing or wrong, pull requests are more than welcome!


<a id="org25f2de9"></a>

# General

| Shortcut  | Binding                                              |
|--------- |---------------------------------------------------- |
| C&#8209;r | redo                                                 |
| u         | undo                                                 |
| y         | evil&#8209;yank                                      |
| Y         | evil&#8209;yank&#8209;line                           |
| .         | evil&#8209;repeat                                    |
| p         | evil&#8209;paste&#8209;after                         |
| P         | evil&#8209;paste&#8209;before                        |
| TAB       | evil&#8209;jump&#8209;forward                        |
| C&#8209;o | evil&#8209;jump&#8209;backward                       |
| %         | evil&#8209;jump&#8209;item                           |
| C&#8209;p | evil&#8209;paste&#8209;pop                           |
| C&#8209;n | evil&#8209;paste&#8209;pop&#8209;next                |
| C&#8209;t | pop&#8209;tag&#8209;mark                             |
| Z Q       | evil&#8209;quit                                      |
| Z Z       | evil&#8209;save&#8209;modified&#8209;and&#8209;close |


<a id="org269586b"></a>

# Prefix commands

| Shortcut | Binding        |
|-------- |-------------- |
| ESC      | Prefix Command |
| Z        | Prefix Command |
| g        | Prefix Command |
| z        | Prefix Command |
| [        | Prefix Command |
| ]        | Prefix Command |


<a id="org418dc1c"></a>

# Selection

| Shortcut  | Binding                         | Description                 |
|--------- |------------------------------- |--------------------------- |
| g v       | evil&#8209;visual&#8209;restore | Restore previous selection. |
| V         | evil&#8209;visual&#8209;line    | Linewise selection          |
| v         | evil&#8209;visual&#8209;char    | Characterwise selection     |
| C&#8209;v | evil&#8209;visual&#8209;block   | Blockwise selection         |


<a id="orgd606561"></a>

# Navigation

| Shortcut        | Binding                                                                                 | Description                                                                        |
|--------------- |--------------------------------------------------------------------------------------- |---------------------------------------------------------------------------------- |
| RET             | evil&#8209;ret                                                                          |                                                                                    |
| '               | evil&#8209;goto&#8209;mark&#8209;line                                                   |                                                                                    |
| \`              | evil&#8209;goto&#8209;mark                                                              |                                                                                    |
| &vert;          | evil&#8209;goto&#8209;column                                                            |                                                                                    |
| o               | evil&#8209;open&#8209;below                                                             |                                                                                    |
| O               | evil&#8209;open&#8209;above                                                             |                                                                                    |
| H               | evil&#8209;window&#8209;top                                                             |                                                                                    |
| M               | evil&#8209;window&#8209;middle                                                          |                                                                                    |
| L               | evil&#8209;window&#8209;bottom                                                          |                                                                                    |
| C&#8209;y       | evil&#8209;scroll&#8209;line&#8209;up                                                   |                                                                                    |
| C&#8209;e       | evil&#8209;scroll&#8209;line&#8209;down                                                 |                                                                                    |
| C&#8209;b       | evil&#8209;scroll&#8209;page&#8209;up                                                   |                                                                                    |
| C&#8209;f       | evil&#8209;scroll&#8209;page&#8209;down                                                 |                                                                                    |
| C&#8209;d       | evil&#8209;scroll&#8209;down                                                            |                                                                                    |
| z t             | evil&#8209;scroll&#8209;line&#8209;to&#8209;top                                         |                                                                                    |
| z z             | evil&#8209;scroll&#8209;line&#8209;to&#8209;center                                      |                                                                                    |
| z b             | evil&#8209;scroll&#8209;line&#8209;to&#8209;bottom                                      |                                                                                    |
| z ^             | evil&#8209;scroll&#8209;top&#8209;line&#8209;to&#8209;bottom                            |                                                                                    |
| z +             | evil&#8209;scroll&#8209;bottom&#8209;line&#8209;to&#8209;top                            |                                                                                    |
| z H             | evil&#8209;scroll&#8209;left                                                            |                                                                                    |
| z L             | evil&#8209;scroll&#8209;right                                                           |                                                                                    |
| z h             | evil&#8209;scroll&#8209;column&#8209;left                                               |                                                                                    |
| z l             | evil&#8209;scroll&#8209;column&#8209;right                                              |                                                                                    |
| z O             | evil&#8209;open&#8209;fold&#8209;rec                                                    |                                                                                    |
| z a             | evil&#8209;toggle&#8209;fold                                                            |                                                                                    |
| z o             | evil&#8209;open&#8209;fold                                                              |                                                                                    |
| z c             | evil&#8209;close&#8209;fold                                                             |                                                                                    |
| z r             | evil&#8209;open&#8209;folds                                                             |                                                                                    |
| z m             | evil&#8209;close&#8209;folds                                                            |                                                                                    |
| C&#8209;w       | evil&#8209;window&#8209;map                                                             |                                                                                    |
| C&#8209;z       | evil&#8209;emacs&#8209;state                                                            |                                                                                    |
| C-]             | evil&#8209;jump&#8209;to&#8209;tag                                                      |                                                                                    |
| C-^             | evil&#8209;buffer                                                                       |                                                                                    |
| &#60;up&#62;    | evil&#8209;previous&#8209;visual&#8209;line                                             |                                                                                    |
| &#60;down&#62;  | evil&#8209;next&#8209;visual&#8209;line                                                 |                                                                                    |
| &#60;left&#62;  | evil&#8209;backward&#8209;char                                                          |                                                                                    |
| &#60;right&#62; | evil&#8209;forward&#8209;char                                                           |                                                                                    |
| SPC             | evil&#8209;forward&#8209;char                                                           |                                                                                    |
| j               | evil&#8209;next&#8209;visual&#8209;line                                                 |                                                                                    |
| k               | evil&#8209;previous&#8209;visual&#8209;line                                             |                                                                                    |
| g j             | evil&#8209;next&#8209;visual&#8209;line                                                 |                                                                                    |
| g k             | evil&#8209;previous&#8209;visual&#8209;line                                             |                                                                                    |
| g 0             | evil&#8209;beginning&#8209;of&#8209;visual&#8209;line                                   |                                                                                    |
| g $             | evil&#8209;end&#8209;of&#8209;visual&#8209;line                                         |                                                                                    |
| w               | evil&#8209;forward&#8209;word&#8209;begin                                               |                                                                                    |
| W               | evil&#8209;forward&#8209;WORD&#8209;begin                                               |                                                                                    |
| e               | evil&#8209;forward&#8209;word&#8209;end                                                 |                                                                                    |
| E               | evil&#8209;forward&#8209;WORD&#8209;end                                                 |                                                                                    |
| b               | evil&#8209;backward&#8209;word&#8209;begin                                              |                                                                                    |
| B               | evil&#8209;backward&#8209;WORD&#8209;begin                                              |                                                                                    |
| g e             | evil&#8209;backward&#8209;word&#8209;end                                                |                                                                                    |
| g E             | evil&#8209;backward&#8209;WORD&#8209;end                                                |                                                                                    |
| g g             | evil&#8209;goto&#8209;first&#8209;line                                                  |                                                                                    |
| G               | evil&#8209;goto&#8209;line                                                              | Go to the first non&#8209;blank character of line COUNT. By default the last line. |
| g m             | evil&#8209;middle&#8209;of&#8209;visual&#8209;line                                      |                                                                                    |
| g ,             | goto&#8209;last&#8209;change&#8209;reverse                                              |                                                                                    |
| g ;             | goto&#8209;last&#8209;change                                                            |                                                                                    |
| g d             | evil&#8209;goto&#8209;definition                                                        |                                                                                    |
| $               | evil&#8209;end&#8209;of&#8209;line                                                      |                                                                                    |
| )               | evil&#8209;forward&#8209;sentence&#8209;begin                                           |                                                                                    |
| (               | evil&#8209;backward&#8209;sentence&#8209;begin                                          |                                                                                    |
| +               | evil&#8209;next&#8209;line&#8209;first&#8209;non&#8209;blank                            |                                                                                    |
| ^               | evil&#8209;first&#8209;non&#8209;blank                                                  |                                                                                    |
| \_              | evil&#8209;next&#8209;line-1-first&#8209;non&#8209;blank                                |                                                                                    |
| g \_            | evil&#8209;last&#8209;non&#8209;blank                                                   |                                                                                    |
| 0               | evil&#8209;digit&#8209;argument&#8209;or&#8209;evil&#8209;beginning&#8209;of&#8209;line |                                                                                    |
| g ^             | evil&#8209;first&#8209;non&#8209;blank&#8209;of&#8209;visual&#8209;line                 |                                                                                    |
| h               | evil&#8209;backward&#8209;char                                                          |                                                                                    |
| l               | evil&#8209;forward&#8209;char                                                           |                                                                                    |
| [ (             | evil&#8209;previous&#8209;open&#8209;paren                                              |                                                                                    |
| [ [             | evil&#8209;backward&#8209;section&#8209;begin                                           |                                                                                    |
| [ ]             | evil&#8209;backward&#8209;section&#8209;end                                             |                                                                                    |
| [ s             | evil&#8209;prev&#8209;flyspell&#8209;error                                              |                                                                                    |
| [ {             | evil&#8209;previous&#8209;open&#8209;brace                                              |                                                                                    |
| ] )             | evil&#8209;next&#8209;close&#8209;paren                                                 |                                                                                    |
| ] [             | evil&#8209;forward&#8209;section&#8209;end                                              |                                                                                    |
| ] ]             | evil&#8209;forward&#8209;section&#8209;begin                                            |                                                                                    |
| ] s             | evil&#8209;next&#8209;flyspell&#8209;error                                              |                                                                                    |
| ] }             | evil&#8209;next&#8209;close&#8209;brace                                                 |                                                                                    |


<a id="orgc65feeb"></a>

# Searching / Finding

| Shortcut | Binding                                                               |
|-------- |--------------------------------------------------------------------- |
| #        | evil&#8209;search&#8209;word&#8209;backward                           |
| \*       | evil&#8209;search&#8209;word&#8209;forward                            |
| &#47;    | evil&#8209;search&#8209;forward                                       |
| ?        | evil&#8209;search&#8209;backward                                      |
| N        | evil&#8209;search&#8209;previous                                      |
| n        | evil&#8209;search&#8209;next                                          |
| g #      | evil&#8209;search&#8209;unbounded&#8209;word&#8209;backward           |
| g \*     | evil&#8209;search&#8209;unbounded&#8209;word&#8209;forward            |
| g N      | evil&#8209;previous&#8209;match                                       |
| g n      | evil&#8209;next&#8209;match                                           |
| ,        | evil&#8209;repeat&#8209;find&#8209;char&#8209;reverse                 |
| ;        | evil&#8209;repeat&#8209;find&#8209;char                               |
| F        | evil&#8209;find&#8209;char&#8209;backward                             |
| T        | evil&#8209;find&#8209;char&#8209;to&#8209;backward                    |
| f        | evil&#8209;find&#8209;char                                            |
| t        | evil&#8209;find&#8209;char&#8209;to                                   |
| g f      | find&#8209;file&#8209;at&#8209;point                                  |
| g F      | evil&#8209;find&#8209;file&#8209;at&#8209;point&#8209;with&#8209;line |
| g C-]    | find&#8209;tag                                                        |


<a id="org586c5ff"></a>

# Editing

| Shortcut | Binding                                     |                                                                                                                                                                                                                     |
|-------- |------------------------------------------- |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| &#60;    | evil&#8209;shift&#8209;left                 |                                                                                                                                                                                                                     |
| &#61;    | evil&#8209;indent                           |                                                                                                                                                                                                                     |
| &#62;    | evil&#8209;shift&#8209;right                |                                                                                                                                                                                                                     |
| A        | evil&#8209;append&#8209;line                |                                                                                                                                                                                                                     |
| C        | evil&#8209;change&#8209;line                |                                                                                                                                                                                                                     |
| D        | evil&#8209;delete&#8209;line                |                                                                                                                                                                                                                     |
| I        | evil&#8209;insert&#8209;line                |                                                                                                                                                                                                                     |
| S        | evil&#8209;change&#8209;whole&#8209;line    |                                                                                                                                                                                                                     |
| X        | evil&#8209;delete&#8209;backward&#8209;char |                                                                                                                                                                                                                     |
| J        | evil&#8209;join                             |                                                                                                                                                                                                                     |
| R        | evil&#8209;replace&#8209;state              |                                                                                                                                                                                                                     |
| a        | evil&#8209;append                           |                                                                                                                                                                                                                     |
| c        | evil&#8209;change                           |                                                                                                                                                                                                                     |
| d        | evil&#8209;delete                           |                                                                                                                                                                                                                     |
| i        | evil&#8209;insert                           |                                                                                                                                                                                                                     |
| x        | evil&#8209;delete&#8209;char                |                                                                                                                                                                                                                     |
| g J      | evil&#8209;join&#8209;whitespace            |                                                                                                                                                                                                                     |
| g U      | evil&#8209;upcase                           |                                                                                                                                                                                                                     |
| g u      | evil&#8209;downcase                         |                                                                                                                                                                                                                     |
| g ~      | evil&#8209;invert&#8209;case                |                                                                                                                                                                                                                     |
| g ?      | evil&#8209;rot13                            | ROT13 encrypt text.                                                                                                                                                                                                 |
| g i      | evil&#8209;insert&#8209;resume              | Switch to Insert state at previous insertion point. The insertion will be repeated COUNT times. If called from visual state, only place point at the previous insertion position but do not switch to insert state. |
| g q      | evil&#8209;fill&#8209;and&#8209;move        |                                                                                                                                                                                                                     |
| g w      | evil&#8209;fill                             | Fill text.                                                                                                                                                                                                          |


<a id="orgc80e532"></a>

# Navigation

| Shortcut                     | Binding                                                          |
|---------------------------- |---------------------------------------------------------------- |
| !                            | evil&#8209;shell&#8209;command                                   |
| 1 .. 9                       | digit&#8209;argument                                             |
| K                            | evil&#8209;lookup                                                |
| \\                           | evil&#8209;execute&#8209;in&#8209;emacs&#8209;state              |
| }                            | evil&#8209;forward&#8209;paragraph                               |
| {                            | evil&#8209;backward&#8209;paragraph                              |
| C-6                          | evil&#8209;switch&#8209;to&#8209;windows&#8209;last&#8209;buffer |
| &#60;down&#8209;mouse-1&#62; | evil&#8209;mouse&#8209;drag&#8209;region                         |


<a id="org86b1e3e"></a>

# Window management

| Shortcut              | Binding                                              | Description                                                                                                                                                                                                                                    |
|--------------------- |---------------------------------------------------- |---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| C&#8209;w C&#8209;n   | evil&#8209;window&#8209;new                          |                                                                                                                                                                                                                                                |
| C&#8209;w n           | evil&#8209;window&#8209;new                          |                                                                                                                                                                                                                                                |
| C&#8209;w C&#8209;c   | evil&#8209;window&#8209;delete                       |                                                                                                                                                                                                                                                |
| C&#8209;w c           | evil&#8209;window&#8209;delete                       |                                                                                                                                                                                                                                                |
| C&#8209;w C&#8209;o   | delete&#8209;other&#8209;windows                     |                                                                                                                                                                                                                                                |
| C&#8209;w o           | delete&#8209;other&#8209;windows                     |                                                                                                                                                                                                                                                |
| C&#8209;w k           | evil&#8209;window&#8209;up                           |                                                                                                                                                                                                                                                |
| C&#8209;w j           | evil&#8209;window&#8209;down                         |                                                                                                                                                                                                                                                |
| C&#8209;w h           | evil&#8209;window&#8209;left                         |                                                                                                                                                                                                                                                |
| C&#8209;w l           | evil&#8209;window&#8209;right                        |                                                                                                                                                                                                                                                |
| C&#8209;w t           | evil&#8209;window&#8209;top&#8209;left               |                                                                                                                                                                                                                                                |
| C&#8209;w C&#8209;t   | evil&#8209;window&#8209;top&#8209;left               |                                                                                                                                                                                                                                                |
| C&#8209;w b           | evil&#8209;window&#8209;bottom&#8209;right           |                                                                                                                                                                                                                                                |
| C&#8209;w C&#8209;b   | evil&#8209;window&#8209;bottom&#8209;right           |                                                                                                                                                                                                                                                |
| C&#8209;w C&#8209;f   | ffap&#8209;other&#8209;window                        | Like ‘ffap’, but put buffer in another window. Only intended for interactive use.                                                                                                                                                              |
| C&#8209;w &#61;       | balance&#8209;windows                                |                                                                                                                                                                                                                                                |
| -w C&#8209;s          | evil&#8209;window&#8209;split                        |                                                                                                                                                                                                                                                |
| C&#8209;w s           | evil&#8209;window&#8209;split                        |                                                                                                                                                                                                                                                |
| C&#8209;w C&#8209;S-s | evil&#8209;window&#8209;split                        |                                                                                                                                                                                                                                                |
| C&#8209;w v           | evil&#8209;window&#8209;vsplit                       |                                                                                                                                                                                                                                                |
| C&#8209;w C&#8209;v   | evil&#8209;window&#8209;vsplit                       |                                                                                                                                                                                                                                                |
| C&#8209;w S           | evil&#8209;window&#8209;split                        |                                                                                                                                                                                                                                                |
| C&#8209;w R           | evil&#8209;window&#8209;rotate&#8209;upwards         |                                                                                                                                                                                                                                                |
| C&#8209;w r           | evil&#8209;window&#8209;rotate&#8209;downwards       |                                                                                                                                                                                                                                                |
| C&#8209;w C&#8209;S-r | evil&#8209;window&#8209;rotate&#8209;upwards         |                                                                                                                                                                                                                                                |
| C&#8209;w C&#8209;r   | evil&#8209;window&#8209;rotate&#8209;downwards       |                                                                                                                                                                                                                                                |
| C&#8209;w C-\_        | evil&#8209;window&#8209;set&#8209;height             |                                                                                                                                                                                                                                                |
| C&#8209;w \_          | evil&#8209;window&#8209;set&#8209;height             |                                                                                                                                                                                                                                                |
| C&#8209;w &vert;      | evil&#8209;window&#8209;set&#8209;width              |                                                                                                                                                                                                                                                |
| C&#8209;w +           | evil&#8209;window&#8209;increase&#8209;height        |                                                                                                                                                                                                                                                |
| C&#8209;w -           | evil&#8209;window&#8209;decrease&#8209;height        |                                                                                                                                                                                                                                                |
| C&#8209;w &#62;       | evil&#8209;window&#8209;increase&#8209;width         |                                                                                                                                                                                                                                                |
| C&#8209;w &#60;       | evil&#8209;window&#8209;decrease&#8209;width         |                                                                                                                                                                                                                                                |
| C&#8209;w w           | evil&#8209;window&#8209;next                         |                                                                                                                                                                                                                                                |
| C&#8209;w C&#8209;w   | evil&#8209;window&#8209;next                         |                                                                                                                                                                                                                                                |
| C&#8209;w W           | evil&#8209;window&#8209;prev                         |                                                                                                                                                                                                                                                |
| C&#8209;w C&#8209;S-w | evil&#8209;window&#8209;prev                         |                                                                                                                                                                                                                                                |
| C&#8209;w C&#8209;p   | evil&#8209;window&#8209;mru                          | Move the cursor to the previous (last accessed) buffer in another window. More precisely, it selects the most recently used buffer that is shown in some other window, preferably of the current frame, and is different from the current one. |
| C&#8209;w p           | evil&#8209;window&#8209;mru                          |                                                                                                                                                                                                                                                |
| C&#8209;w K           | evil&#8209;window&#8209;move&#8209;very&#8209;top    |                                                                                                                                                                                                                                                |
| C&#8209;w C&#8209;S-k | evil&#8209;window&#8209;move&#8209;very&#8209;top    |                                                                                                                                                                                                                                                |
| C&#8209;w J           | evil&#8209;window&#8209;move&#8209;very&#8209;bottom |                                                                                                                                                                                                                                                |
| C&#8209;w C&#8209;S-j | evil&#8209;window&#8209;move&#8209;very&#8209;bottom |                                                                                                                                                                                                                                                |
| C&#8209;w H           | evil&#8209;window&#8209;move&#8209;far&#8209;left    |                                                                                                                                                                                                                                                |
| C&#8209;w C&#8209;S-h | evil&#8209;window&#8209;move&#8209;far&#8209;left    |                                                                                                                                                                                                                                                |
| C&#8209;w L           | evil&#8209;window&#8209;move&#8209;far&#8209;right   |                                                                                                                                                                                                                                                |
| C&#8209;w C&#8209;S-l | evil&#8209;window&#8209;move&#8209;far&#8209;right   |                                                                                                                                                                                                                                                |


<a id="orgb129dd2"></a>

# Bindings starting with g

| Shortcut | Binding                          |
|-------- |-------------------------------- |
| g 8      | what&#8209;cursor&#8209;position |
| g a      | what&#8209;cursor&#8209;position |


<a id="orgd81d16b"></a>

# Macro

| Shortcut           | Binding                        |
|------------------ |------------------------------ |
| @                  | evil&#8209;execute&#8209;macro |
| q                  | evil&#8209;record&#8209;macro  |
| z RET              | Keyboard Macro                 |
| z -                | Keyboard Macro                 |
| z .                | Keyboard Macro                 |
| z &#60;left&#62;   | Keyboard Macro                 |
| z &#60;return&#62; | Keyboard Macro                 |
| z &#60;right&#62;  | Keyboard Macro                 |


<a id="orgf54d111"></a>

# Other

| Shortcut | Binding                                                  |
|-------- |-------------------------------------------------------- |
| "        | evil&#8209;use&#8209;register                            |
| m        | evil&#8209;set&#8209;marker                              |
| r        | evil&#8209;replace                                       |
| s        | evil&#8209;substitute                                    |
| ~        | evil&#8209;invert&#8209;char                             |
| DEL      | evil&#8209;backward&#8209;char                           |
| C-.      | evil&#8209;repeat&#8209;pop                              |
| M-.      | evil&#8209;repeat&#8209;pop&#8209;next                   |
| :        | evil&#8209;ex                                            |
| &        | evil&#8209;ex&#8209;repeat&#8209;substitute              |
| g &      | evil&#8209;ex&#8209;repeat&#8209;global&#8209;substitute |