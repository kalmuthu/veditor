v editor
---------

Source code development and navigation tool

Steps for intallation:
----------------------
1. Copy the vinstall file to your home directory
2. Run the installation file "./vinstall"
3. Done!

Note: 
  During the installation, installation script will take backup of your old .bash*, .vim*, .screenrc*, .netrc* and few other . xx files and will be stored in backup folder in home directory.

Steps for Running:
----------------------
1. Go to source code base folder 
2. Run the "gtags" command
3. Done!
  
## DOCUMENTATION
Jump to definition ( CTRL + \\) or (CTRL + xx) or ( CTRL +])
![](https://github.com/kalmuthu/v-editor/blob/master/docs/definition.png)


Jump to Reference ( CTRL + r) or (CTRL + r + r)
![](https://github.com/kalmuthu/v-editor/blob/master/docs/reference.png)



Find files (CTRL + p + p)
![](https://github.com/kalmuthu/v-editor/blob/master/docs/path.png)



Find raw strings ( CTRL + g), Find regex strings (CTRL + gg) 
![](https://github.com/kalmuthu/v-editor/blob/master/docs/grep.png)


Auto complete( just press . or -> )
![](https://github.com/kalmuthu/v-editor/blob/master/docs/autocomplete.png)


Find within a file or find within a search result( CTRL + SS)
![](https://github.com/kalmuthu/v-editor/blob/master/docs/sub-pattern.png)

Navigation List ( CTRL + T)
![](https://github.com/kalmuthu/v-editor/blob/master/docs/taglist.png)

Jump/return Back to previous navigation  (CTRL + D), Close current Tag(CTRL + D)
![](https://github.com/kalmuthu/v-editor/blob/master/docs/grep.png)

Multiple Word highlight/unhighlight ( CTRL + &lt;SPACE&gt; )
![](https://github.com/kalmuthu/veditor/blob/master/docs/highlight.png)


Seach with KG tools (CTRL + FF)
![](https://github.com/kalmuthu/veditor/blob/master/docs/kg_search.png)


Background Theme 
~/.vimrc: let g:vim_background_color_scheme  = 'klight'
![](https://github.com/kalmuthu/veditor/blob/master/docs/bg_klight.png)

~/.vimrc: let g:vim_background_color_scheme  = 'kdark'
![](https://github.com/kalmuthu/veditor/blob/master/docs/bg_kdark.png)


Multiple Cliboard Copy and Paste
Copy:
1. Select + Yank (CTRL+v / SHIFT +V +  Y)

2. Select + Yank (CTRL+v / SHIFT +V +  Y)

3. Select + Yank (CTRL+v / SHIFT +V +  Y)

Paste:
3. Paste last (CTRL + P / CTRL + N)

2. Paste Second last ( CTRL+P CTRL+P / CTRL+N CTRL+N)

1. Paste third last ( CTRL+P CTRL+P CTRL+P / CTRL+N CTRL+N CTRL+N)

  and so on...


Auto complete
X-PATTERN: sym&lt;TAB&gt;&lt;TAB>   =&gt; Symbol automplete
R-PATTERN: sym&lt;TAB&gt;&lt;TAB>   =&gt; Symbol automplete
P-PATTERN: file&lt;TAB&gt;&lt;TAB>  =&gt; File name  automplete


Comment/Uncomment source code lines:

To Comment:

  Selete block + &lt;CTRL + C&gt;


To UnComment:
  
  Selete block + &lt;CTRL + X&gt;

----------------------------------------------------

BASH Commands
-------------


x &lt;symbol name&gt;   =&gt; Open the vim and jumps to definition
r &lt;symbol name&gt;   =&gt; Open the vim and list all the references
p &lt;file name&gt;     =&gt; Open the file in vim 


TAB Completion:
--------------
x  sym&lt;TAB>&lt;TAB>  => Auto complete the symbol
