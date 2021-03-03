# SHELL SCRIPTING

- the first line of the script should specify the shell type for interpreter. It is called `shebang`
- `chmod +x filename` makes file executable. `r, x, w` all of them could used separately and combined.
- the UID of root user is always 0.
- `cat /etc/shells` list all the available shells.
- `cat $0` shows currently using shell
- `cat $SHELL` shows location of the current shell.
- variables can be exported and used by other shells. `export myvar=skills`
- multi line comments can be added with

```
: '
this is multi line
comment
'
```

- `$0` represents the file itself in the script.
- `args=("$@")` args can be taken as an array like this.
- `$@` is the holds all the arguments.
- `$#` will give the length of the array.
