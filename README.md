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

Multiple Word highlight/unhighlight ( <SPACE> )
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

Comment/Uncomment source code lines:
Comment:
    Selete block + <CTRL + C>


Comment:
    Selete block + <CTRL + X>


.VIMRC customization
"==================================================================
"                                       GTAGS KEY BINDINGS
"==================================================================

let g:gtags_open_defination             = '<C-\>' <BR>
let g:gtags_open_defination_left_hand   = '<C-E>' <BR>              "
let g:gtags_open_defination_ctags_stype = '<C-]>' <BR>
let g:gtags_open_reference              = '<C-R>' <BR>
let g:gtags_open_local_sym_reference    = '<C-S>'
let g:gtags_open_raw_string_search      = '<C-G>'
let g:gtags_open_navigation_path        = '<C-T>'
let g:gtags_close_tag                   = '<C-D>'

let g:gtags_cmd_open_kg_search          = '<C-F><C-F>'
let g:gtags_cmd_open_definition         = '<C-X><C-X>'
let g:gtags_cmd_open_reference          = '<C-R><C-R>'
let     g:gtags_cmd_open_grep_search    = '<C-G><C-G>'
let     g:gtags_cmd_open_file_path              = '<C-P><C-P>'
let     g:gtags_cmd_sub_string_search   = '<C-S><C-S>'
let     g:gtags_cmd_search_and_replace  = '<C-F><C-R>'
let     g:gtags_cmd_view_cursor_file    = '<C-F><C-L>'


"==================================================================
"                                       VIMRC KEY BINDINGS
"==================================================================
let g:toggle_paste_mode                         = '<F4>'
let g:insert_cfile_header_directive = '<C-F><C-H>'
let g:cmd_full_find_replace                     = '<C-J>'
let g:cmd_line_find_replace                     = '<C-K>'
let g:cmd_select_find_replace           = '<C-L>'
let g:cmd_highlight_word                        = '<SPACE>'

let g:cmd_quit                                          = '<F1>'
let g:cmd_save_file                                     = '<F2>'
let g:cmd_update_gtags_file                     = '<F3>'

let g:cmd_clearcase_check_out           = '<F5>'
let g:cmd_clearcase_check_in            = '<F6>'
let g:cmd_clearcase_update                      = '<F7>'
let g:cmd_clearcase_undo_check_out      = '<F8>'

let g:cmd_insert_function_header        = '<C-F><C-U>'
let g:cmd_align_equal                           = '<C-F><C-E>'

let g:cmd_paste_cycle_next                      = '<C-N>'
let g:cmd_paste_cycle_previous          = '<C-P>'

let g:cmd_load_current_word_find        = '<C-F>'
let g:cmd_load_current_word_gtags       = '<C-D>'


let g:cmd_add_comment                           = '<C-C>'
let g:cmd_remove_comment                        = '<C-X>'

"==================================================================
"                                       VIM BINDINGS
"==================================================================
"let g:vim_background_color_scheme      = 'klight'
let g:vim_background_color_scheme       = 'kdark'


