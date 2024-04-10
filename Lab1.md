# Lab 1 Report
***
## `cd command`

1. For `cd with no arguments`
![Image](cd.png)
> The absolute path for this working directory right before the command is `/Users/audreyliu/Downloads/CSE 15L/lab 1/lecture1`.
> 
> `argument` represents either a file name or a directory name in terminal next command. By typing command `cd` without arguments next to it, it changes the current directory back to home directory by adding `~` behind server name with spaces. In this case, by typing cd without arguments, it changes the working directory back to `/Users/audreyliu`.

2. For `cd with a path to a directory as an argument`
![Image](<cd directory.png>)
> The absolute path for this working directory right before the command is `/Users/audreyliu/Downloads/CSE 15L`.
>
> `a directory` means a title for a file which still has documents under it. `cd` command can only implement directories which are under the current directory. By adding nonexisting or parent directory, it will truns to an error by showing that directory not exist. By typing command `cd` with a directory name, it changes from the current directory to the new typed-in directory. In my example, after typing `cd lab\ 1`, it changes the working directory from `/Users/audreyliu/Downloads/CSE 15L` to `/Users/audreyliu/Downloads/CSE 15L/lab 1`.

3. For `cd with a path to a file as an argument`
![Image](<cd file.png>)
> The absolute path for this working directory right before the command is `/Users/audreyliu/Downloads/CSE 15L/lab 1/lecture1`.
> 
>  `a file` is the title for a ducument which contains information. By typing `cd` with a file name as an argument, it prints out `cd: not a directory: ` plus the `file name` which is the same as an error. Because command cd can only implement a directory, so by sending a file name to it, it will recognize that it is not a directory then return an `error` by printing out that line.

* ## `ls command`
1. For `ls with no arguments`
![Image](ls.png)
> The absolute path for this working directory right before the command is `/Users/audreyliu/Downloads/CSE 15L`.
> 
> `ls` is a command which will list all the directories' and files' names. By typing ls without argument, it prints out `all the directories' and files' name for the current directory`. 

2. For `ls with a path to a directory as an argument`
![Image](<ls directory.png>)
>The absolute path for this working directory right before the command is `/Users/audreyliu/Downloads/CSE 15L`.
>
>The directory name after "ls" must be exist and inside of the current directory, otherwise, it will truns to an error. Typing `ls` with a correct directory name will show `all the directories' and files' name inside the directory name that entered`.

3. For `ls with a path to a file as an argument`
![Image](<ls file.png>)
> The absolute path for this working directory right before the command is `/Users/audreyliu/Downloads/CSE 15L/lab 1/lecture1/messages`.
>
> The file name next to the "ls" command must be exist under the current directory, otherwise, it will turns to an error by showing the file does not exist. Typing "ls" with a file name returns `the exact name of the file as the output`. 

* ## `cat command`
1. For `cat with no arguments`
![Image](cat.png)
> The absolute path for this working directory right before the command is `/Users/audreyliu/Downloads/CSE 15L/lab 1/lecture1/messages`.
>
> Typing `cat` command without any arguments next to it will make it `read the input and print it out`. In the screenshot, "tester" and "sample" are two demos I used to show how "cat" command works. 

2. For `cat with a path to a directory as an argument`
![Image](<cat directory.png>)
> The absolute path for this working directory right before the command is `/Users/audreyliu/Downloads/CSE 15L/lab 1/lecture1`.
>
> Typing `cat` command with a directory's name will print out `cat: ` + the directory's name + `: Is a directory`, which means "cat" can recognize that the file is a directory or a text file, and by showing this output, it can be considered as an error because "cat" cannot read and print a folder/directory. If typing an unexisting file name next to "cat", it returns `cat: ` + file name + `: No such file or directory`, which same as an error as well.

3. For `cat with a path to a file as an argument`
![Image](<cat file.png>)
> The absolute path for this working directory right before the command is `/Users/audreyliu/Downloads/CSE 15L/lab 1/lecture1/messages`.
>
> Typing "cat" with an existing file name under current directory allows "cat" to read, copy, and paste the information from the text file into the terminal. 
