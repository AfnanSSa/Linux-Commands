## `sudo` Command 
`sudo` stands for "superuser do" and allows a permitted user to execute a command as the superuser (root) or another user.
### Usage 
    $ sudo [options] [command]
### Commonly Used Options 
`-b`: runs the command in the background.

`-H`: sets the HOME environment variable to the target user's home directory.

`-h`: displays help information.

`-i`: runs the shell specified by the target user's password database entry as a login shell.

`-k`: invalidates the user's cached credentials.

`-l`: lists the allowed (and forbidden) commands for the invoking user.

`-S`: reads the password from standard input.

`-u`: runs the command as the specified user.