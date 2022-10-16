st - simple terminal
--------------------
st is a simple terminal emulator for X which sucks less.


Requirements
------------
In order to build st you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

    make clean install


Running st
----------
If you did not install st with make clean install, you must compile
the st terminfo entry with the following command:

    tic -sx st.info

See the man page for additional details.
DKEY Mod1Mas

Credits
-------
Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.

patch
------ 
https://st.suckless.org/patches/
从官网下载patch到本地目录
wget xxx.pathc

patch < ~/patch/t-colorschemes-0.8.5.diff

如遇失败可以根据补丁文件手动添加。
每次make前删除config.h文件

## Keyboard
Action      | Key Combination
---         | ---
Copy        | `ctrl` + `shift` + `c`
Paste       | `ctrl` + `shift` + `v`
selPaste    | `ctrl` + `shift` + `y`
Zoom In     | `alt` + `shift` + `+`
Zoom Out    | `alt` + `shift` + `-`
Reset Zoom  | `alt` + `shift` + `0`
Scroll up   | `shift` + `page up`
Scroll down | `shift` + `mouse down`
Scroll up   | `shift` + `mouse up`
Scroll down | `shift` + `page down`
Scroll up/down   | `F11`
selectscheme | `alt` +  `0-9`
selectscheme | `alt` + `ctrl` +  `0`
keyboard_select|`ctrl` + `shift` +  `Esc`

## path
### keyboard_select
当您运行“keyboard_select”时，您有 3 种可用模式：
 - 移动模式：设置选择的开始；
 - 选择模式：激活并设置选择的结束；
 - 输入方式：输入搜索条件。

移动和选择模式的快捷键：
h, j, k, l:    move cursor left/down/up/right (also with arrow keys)
 !, _, *:       move cursor to the middle of the line/column/screen
 Backspace, $:  move cursor to the beginning/end of the line
 PgUp, PgDown : move cursor to the beginning/end of the column
 Home, End:     move cursor to the top/bottom left corner of the screen
 /, ?:          activate input mode and search up/down
 n, N:          repeat last search, up/down
 s:             toggle move/selection mode
 t:             toggle regular/rectangular selection type
 Return:        quit keyboard_select, keeping the highlight of the selection
 Escape:        quit keyboard_select

使用 h,j,k,l（也可以使用箭头键），您可以使用量词。在按下相应的键之前输入一个数字。

输入模式的快捷键：

 Return:       Return to the previous mode

