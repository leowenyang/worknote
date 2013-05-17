vim config  note
==============================
how to get vim help
-------------------------
1. :help {subject}   ==> to show help doc
2. :helptags {dir}   ==> generate help tags for directory {dir}

vim option
-------------------------
### Option Type
These options come in three forms:  

    --------------------------------------
    boolean   | can only be on or off
    number    | has a numeric value
    string    | has a string value
    --------------------------------------

### Manage Option
- List option  ==> set all
- Open option  ==> set {option}
- Close option ==> set no{option}

vim map
-------------------------

    -------------------------------------------------------------------------
    command | Normal | Insert only | command line | Visual | Operator Pending
    ------------------------------------------------------------------------- 
     :nmap  |    Y   |             |              |        |      
     :imap  |        |     Y       |              |        |
     :cmap  |        |             |      Y       |        | 
     :vmap  |        |             |              |   Y    |      
     :omap  |        |             |              |        |      Y
     :map   |    Y   |             |              |   Y    |      Y
     :map!  |        |     Y       |      Y       |        |
    --------------------------------------------------------------------------

vim autocmd
------------------------

autocmd [group] {event} {pat} [nested] {cmd}

    Add {cmd} to the list of commands that Vim will execute automatically on {event} for a file matching {pat}.
    Vim always adds the {cmd} after existing autocommands, so that the autocommands execute in the order in which they were given.
