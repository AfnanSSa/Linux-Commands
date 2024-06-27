## `su` Command 
`su` stands for "switch user". It is used to switch from the current user to another user in a command-line session.
### Usage 
    $ su [options] [username]

### Commonly Used Options 
`-`: Start a login shell (similar to logging in directly as the target user).

`-l`: Same as -, starts a login shell.

`-m` or `-p`: Preserve the current environment, including variables such as HOME and SHELL.

`-c [command]`: Execute a specific command as the target user and then return to the original.