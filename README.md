This repo forked from another resource. You can find the original work in this [repo](https://github.com/rrg/ListOpenFiles).

List Open Files
==========

Generates a [TCL](https://www.tcl.tk/man/tcl8.5/tutorial/Tcl0.html) list of all the open files in current Sublime Text window. Take a [look](https://cnpagency.com/blog/creating-sublime-text-3-plugins-part-1/) for preparing plugin for Sublime Text.


Keybindings
------------

Add a keybinding by going to **Preferences->Key Bindings-User**

My preferred key binding:

    [
       { "keys": ["ctrl+alt+l"], "command": "list_open_files" }
    ]

Command
------------
list_open_files: Creates a [TCL](https://www.tcl.tk/man/tcl8.5/tutorial/Tcl0.html) list of all the open files in Sublime Text.