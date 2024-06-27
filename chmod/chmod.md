## `chmod` Command 
`chmod` changes the permissions (mode) of files and directories.
### Usage
    $ chmod [options] mode file(s)
### Commonly Used Options
`-v`: Verbose mode; display a message for each file processed.

`-c`: Like -v, but only display a message when a change is made.

`-R`: Recursively change permissions for directories and their contents.

`--reference=<file>`: Set permissions to match another file.
### Symbolic Notation:
- User Types: `u` (user/owner), `g` (group), `o` (others), `a` (all, equivalent to ugo).

- Operators: `+` (add permissions), `-` (remove permissions), `=` (set exact permissions).

- Permissions: `r` (read), `w` (write), `x` (execute).