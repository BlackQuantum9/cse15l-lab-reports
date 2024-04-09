# Lab 1 Report
***
* ## `cd command`
1. For `cd with no arguments`
![Image](cd.png)
> The absolute path for this working directory right before the command is "/Users/audreyliu/Downloads/CSE 15L/lab 1/lecture1".
> 
> "argument" represents either a file name or a directory name in terminal next command. By typing command "cd" without arguments next to it, it changes the current directory back to home directory by adding "~" behind server name with spaces.

2. For `cd with a path to a directory as an argument`
![Image](<cd directory.png>)
> The absolute path for this working directory right before the command is "/Users/audreyliu/Downloads/CSE 15L".
>
> "a directory" means a tile for a file which still has documents under it. "cd" command can only implement directories which are under the current directory. By typing command "cd" with a directory name, it changes from the current directory to the new typed in directory.

3. For `cd with a path to a file as an argument`
![Image](<cd file.png>)
> The absolute path for this working directory right before the command is "/Users/audreyliu/Downloads/CSE 15L/lab 1/lecture1".
> 
>  "a file" is the title for a ducument which contains information. By typing "cd" with a file as an argument, it prints out ""cd: not a directory: " plus the file name which is the same as an error. Because command "cd" can only inplement a directory, so by sending a file name to it, it will recognize that it is not a directory then return an error by printing out that line.

* ## `ls command`
1. For `ls with *no* arguments`
![Image](ls.png)
> The absolute path for this working directory right before the command is "/Users/audreyliu/Downloads/CSE 15L".
> 
> "ls" is a command which will list all the directories' and files' names. By typing "ls" without argument, it prints out all the directories' and files' name for the current directory. 

2. For `ls with a path to a *directory* as an argument`
![Image](<ls directory.png>)
>The absolute path for this working directory right before the command is "/Users/audreyliu/Downloads/CSE 15L".
>
>Typing "ls" with a directory name will show all the directories' and files' name inside the directory that entered.

3. For `ls with a path to a *file* as an argument`
![Image](<ls file.png>)
> The absolute path for this working directory right before the command is "/Users/audreyliu/Downloads/CSE 15L/lab 1/lecture1/messages".
>
> Typing "ls" with a file name next it returns the name of the file as the output. 

* ## `cat command`
1. For `cat with *no* arguments`
![Image](cat.png)
> The absolute path for this working directory right before the command is "/Users/audreyliu/Downloads/CSE 15L/lab 1/lecture1/messages".
>
> Typing "cat" command without any arguments next it will make it read the input and reprint it out. In the screenshot, "tester" and "sample" are two demo I used to show how "cat" command works. 

3. For `cat with a path to a *directory* as an argument`
![Image](<cat directory.png>)
> The absolute path for this working directory right before the command is "/Users/audreyliu/Downloads/CSE 15L/lab 1/lecture1".
>
> Typing "cat" command with a directory's name will print out "cat: " + the directory's name + ": Is a directory", which means "cat" can recognize that the file is a directory or a text file. And by printing out that line, it can be considered as an error because "cat" cannot read and print a folder/directory.
>
> by typing an unexisting file name next to "cat", it returns "cat: tester.txt: No such file or directory", which same as an error.

5. For `cat with a path to a *file* as an argument`
![Image](<cat file.png>)
