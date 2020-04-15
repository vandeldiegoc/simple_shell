# simple shell
This is a program that provides a command line interpreter. allowing read commands and run other programs.

## Functions used

|FUNTION | DESCRIPTION|
| ------------- | ------------------------------ |
| `_strdup()`   | **returns a pointer to a newly allocated space in memory**     |
| `_puts()`  | **prints a string**     |
| `puts_grid()`   | **prints vertically the elem. of a grid**     |
| `shell_read()`   | **get the line**     |
| `shell_token()`   | **Separate a line into tokens**     |
| `_realloc()`   | **reallocates a memory block**     |
| `_puts_grid()` | **Destroy your computer!**     |
| `shell_process()`   | **create a child process and wait until it ends**     |
| `shell_status()`   | **determines if the tokens are executable or not**     |
| `_getenv(()`   | **get the content of an env. var.**     |
| `_strcat()`   | **concatenates two strings**     |
| `_strcpy()`   | **copy from src to dest**     |
| `_strcmp()`   | **compares two strings**     |
| `grid_cpy()`   | **  copy from src to dest**     |
| `path_exe()`   | ** create a child process and wait until it ends**     |
|`shell_path()`   | ** look if the token is a file in the path dir**     |
|`shell_loop()`   | ** wait for a string a process it**     |
|`shell_builtins()`   | ** compares the and runs the argument 0 if it is exit or env**     |
|`puts_grid()`   | ** prints vertically the elem. of a grid**     |
|`_strlen`   | ** returns the length of a string**     |
|` _putchar()`   | ** writes the character c to stdout**     |
|`var_con()`   | ** returns the content of a var**     |
|`_strmatch()`   | **  looks if the var exists**     |
|`var_name()`   | ** find the var name in the i pos.**  |
##command
- [x] ls  -[argument]
- [x] exit
- [x] env
- [ ] cd
- [ ] |
## use
1. clone this  repository.
2. compile the code using:
       gcc  -Wall -Werror -Wextra -pedantic * .c -o hsh
3. enter your command.

## example
      vda@vda-M2420:~/Documentos/simple_sheel$ ./hsh 
      $ ls
      _getenv.c   _strcat.c  a.out	    shell.h	      shell_process.c
      _putchar.c  _strcmp.c  hsh	    shell_buitlins.c  shell_read.c
      _puts.c     _strcpy.c  main.c	    shell_loop.c      shell_status.c
      _realloc.c  _strdup.c  puts_grid.c  shell_path.c      shell_token.c
      $ pwd    
      /home/vda/Documentos/simple_sheel
      $ exit	
      vda@vda-M2420:~/Documentos/simple_sheel$

## Authors
- [Adonis Tejeda](https://github.com/adonis7ejeda "Adonis Tejeda")
- [Diego Vivius](https://github.com/vandeldiegoc "Diego Vivius")

