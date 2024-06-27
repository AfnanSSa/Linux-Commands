## `nano` Command
`nano` launches the Nano text editor, a simple and easy-to-use command-line text editor.
### Usage 
    $ nano [options] [file]
### Commonly Used Options 
`-B`: creates backup files when saving.

`-C`: stores backup files in the specified directory.

`-m` Enable mouse support.

`-R`: restricted mode (some functions like file writing are disabled).

`-v`: views-only mode (disable all editing functions).

`-w`: disables line wrapping.
### Basic `nano` Commands 
`Ctrl + G`: displays help.

`Ctrl + X`: exits Nano.

`Ctrl + O`: writes (save) the file.

`Ctrl + R`: reads a file into the current buffer.

`Ctrl + K`: cuts the current line.

`Ctrl + U`: uncuts (paste) the last cut line.

`Ctrl + _`: goes to a specific line number.

`Ctrl + W`: searches for a string or pattern.

`Ctrl + O`: saves the current file. Nano will prompt for a file name if the file is new.

`Ctrl + X`: exits Nano. If there are unsaved changes, Nano will prompt you to save the file.