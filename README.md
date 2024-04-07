# Vim
## Basic instrucments
* install:
```
>sudo apt install vim
```
* Use vim
```
>vi editfile
>vim editfile
```
* Ternimal mode: 'Esc'
* Quit: 
	* ':q': quit
	* ':q!': quit and not save change
	* ':wq': quit and save change
* Insert (edit mode):
	* 'i'
	* Shift + 'i': insert in beginning of current line
	* 'a': insert in next current character
	* 'o': insert with newline
	* 's': insert with erase next current character
* Save:
	* ':w'
* Undo:
	* 'u'
	* number + 'u': undo x times
* Redo:
	* Ctrl + 'R'
	* number + Ctrl + 'R': redo x times
* Select multiple words:
	* 'v' + move arrows
	* Use number + arrows to select work faster
	* 'yy': Copy one line
* Delete with key:
	* 'd' + move: delete words and line with direction arrow
	* 'v' -> 'd': delete words are selected by 'v'
	* 'dd': delete one line 
	* number + 'dd': delete number line
* Past:
	* 'v' -> 'y' -> 'p': copy and past
	* 'v' -> 'd' -> 'p': cut and past
	* Mutiple past: number + 'p'	
## Advance instrucment
* Number line editor:
	* ':set number'
	* ':set relativenumber': see number line by format 'current line - another line', more convenient for move line with below 'Move faster...'
* Move faster with number line: in terminal mode, typing 'number' and 'move'
	* Example: move from line 1 to line 20 in one 'move key': '20' -> move down
* More convenient way to move pointer:
	* 'h': move to begin
	* 'l': move to end
	* 'j': move to bottom
	* 'k': move to top
* Adjust tab:
	* :set tabstop=5
* Change theme color:
	* :colorscheme + 'Tab' -> choose color
* Save Setting mode:
	* Config file ~/.vimrc.
	```
	>cp config.txt ~/.vimrc
	```
	* Modify setting vim
	```
	>vi ~/.vimrc
	```
## Full tutorial
* [FreeCodeCamp.org](https://www.youtube.com/watch?v=RZ4p-saaQkc&list=LL&index=9&t=359s)
	 <!-- Current 30:00 -->
* [Vim cheat Sheet](https://vim.rtorr.com/)
* Look more intuitive, [Vim cheatSheet look easier](https://devhints.io/vim)
	![](vim-cheatsheet.png)

