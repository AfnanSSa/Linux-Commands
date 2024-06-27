## `ps` Command
`ps` displays information about currently running processes.
### Usage 
    $ ps [options]
### Commonly Used Options
`-e`: displays information about all processes, not just those associated with the terminal session.

`-f`: displays full-format listing, showing more details about each process.

`-l`: Long format listing, providing additional details such as process UID (user ID) and PPID (parent process ID).

`-u <user>`: displays processes owned by a specific user.

`-p <pid>`: displays information for a specific process ID (PID).

`-aux` or `-ef`: displays all processes in a full listing format, including user, CPU usage, memory usage, etc.