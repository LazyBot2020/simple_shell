# simple Shell

* Display a prompt and wait for the user to type a command. A command line always ends with a new line.
* If an executable cannot be found, print an error message and display the prompt again.
* Handle errors.
* Hndling the “end of file” condition (Ctrl+D)
* Hanling the command line with arguments
* Handle the PATH
* Support the exit features and the exit status
* Handle the Ctrl-C to not terminate the shell
* Handling the command seperator `;`
* Handling `&&` and `||` logical operators
* Handle variable replacements `$?` and `$$`
* Handle the comments `#`
* Support the history feature
* Support the file input

## files

AUTHORS    builtin.c   errors.c   getLine.c  history.c  main.c    realloc.c     string.c     vars.c
README.md  builtin1.c  errors1.c  getenv.c   lists.c    memory.c  shell.h       string1.c
_atoi.c    environ.c   exits.c    getinfo.c  lists1.c   parser.c  shell_loop.c  tokenizer.c

