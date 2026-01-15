# 10 Terminal Tricks that Can Make Life Easier

The very thought of terminal can give you goosebumps, if you are new to Linux. However, there are some useful commands that can make the use of terminal beneficial for productivity. 

## Search the command history

There is a useful command to search the command history:

!!
Ctrl + R
!!

## Clear the Screen without Clearing the History

There is another command to clear the screen without clearing the screen.

!!
Ctrl + L
!!

## Auto complete like a Pro

Sometimes it can be tricky to enter a file nam. SO, the best thing is to clic on Tab once to complete the file name.

You can also press Tab twice to list all the possibilities.

## Pipe commands together

You can also join the commands together, if the output of command is the input for the next command.

You can do so by using the character pipe - | at the end of first command. 

## Redirst the output to a file

YOu caneven use a character to save the output of a command in a file. The character is >.

Example:

!!
ls -la > file.txt
!!

## Find files instantly

In order to find a file instantly, you can use the command:

!!
find . -name "*.log"
!!

## Kill Frozen Applications or Programs

To kill a frozen application or a program that is not responding, you can use the command:

!!
kill PID
!!

Here, to know the PID you eed to enter the following command first:

!!
ps aux
!!

## 