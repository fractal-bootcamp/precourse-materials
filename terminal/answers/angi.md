# TERMINAL

## QUESTIONS

### What are the top 20 commands for mac Command Line Interface (CLI)?
1. cd
- change to a different working directory
-  usage: cd “path/to/directory/”

2. ls
- list contents of directory, can add arguments like -l to get more information about files
- usage: ls "path/to/directory/"

3. open
- open a file with an appropriate app, can partially type filename and press tab to autocomplete
- usage: open "filename"

4. cp
- copy file to another directory
- usage: cp "filenamepath" "newfilenamepath"

5. mv
- move file to a new location
- usage: mv "filenamepath" "newfilenamepath"

6. touch
- create a blank file of any type, can use open command afterwards
- usage: touch myfile.txt

7. mkdir
- create a directory
- usage: mkdir "path/to/new/directory"

8. rmdir
- remove a directory
- usage: rmdir "path/to/directory"

9. rm -R
- remove nested directories and contents recursively, note this is irreversible and cannot restore files afterwards from Trash
- usage: rm -R “/path/to/directory"

10. sudo
- execute commands with superuser privileges, use for example removing a file owned by another user
- usage: sudo "command"

11. top
- list actively running processes, see stats like memory, CPU, disk utilization, ports used, will execute until ctrl-C or close terminal window
- usage: top

12. q
- quit subscreen for commands that run perpetually like top, alternative to ctrl-C
- usage: q

13. clear
- clear terminal screen of all previous commands
- usage: clear, or cmd-K

14. ditto
- copy contents of one folder to another folder, can use -V to gget verbose output for each file copied
- usage: ditto -V folder newfolder

15. whatis
- get one-line description for a command
- usage: whatis "command"

16. man
- show manual page for a command
- usage: man "command"

17. exit
- close out current session in terminal, can use when closing out window is not available eg. when using ssh to close remote connection
- usage: exit

18. shortcuts run
- run Apple shortcut workflow
- usage: shortcuts run "myshortcut"

19. tmutil startbackup
- start a new Time Machine backup snapshot
- usage: tmutil startbackup

20. killall
- force quit an app
- usage: killall "appname"

(https://www.techrepublic.com/article/16-terminal-commands-every-user-should-know/)

### What is a terminal? A CLI? Why are they synonymous?
- Terminal is originally referred to a physical device (like a keyboard and monitor) used to interact with a computer. Today it usually refers to terminal emulators or software like the mac terminal app. 
- CLI is a way of interacting with software by typing text commands, as opposed to using a GUI. 
- A CLI can run inside a terminal but isn't the terminal itself, but in casual conversations people interchange the terms

(chatGPT)

### What is the difference between bash and zsh?

These are different Linux shell environments. 
- Bash was created by the GNU project to be part of its free operating system, named after "Bourne Again shell". First released in 1989, it is the default shell on most Linux distributions and on Apple's macOS. 
- Z shell, or "zsh" is a popular newer shell, a Bourne-style shell that contains the features in bash, plus even more. For example, zsh has spell-checking, the ability to watch for logins/logouts, some built-in programming features like bytecode, support for scientific notation in syntax, allows for floating-point arithmetic, and more features.

(https://www.howtogeek.com/68563/htg-explains-what-are-the-differences-between-linux-shells/)

### What is the difference between Terminal, Console, Shell, and Command Line?
- terminal = text input/output environment
- console = physical terminal
- shell = command line interpreter
- command line = interface where you type text commands, usually within a shell, accessed through a terminal

(https://askubuntu.com/questions/506510/what-is-the-difference-between-terminal-console-shell-and-command-line, chatGPT)