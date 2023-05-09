---
name: Anais Martinez
semester: spring 23
course: cis106
---

# Question 1

## awk
* Description
Awk is a scripting language used for processing and displaying text. Awk performs operations line by line.

* Formula 
'awk + options + {awk command} + file + file to save (optional)'

* Examples
  * Print the first column of every line of a file
    * 'awk '{print $1} ~/Documents/Csv/cars.csv'
  * Print first field of /etc/passwd file
    * 'awk -F: '{print $1}' /etc/passwd'
  * Print the last field of the /etc/passwd file
    * 'awk -F: '{print $NF}' /etc/passwd'

## cat
* Description
The cat command is used for displaying the content of a file.

* Formula 
'cat + option +file(s) to display'
* Examples
  * Display the content of a file located in the pwd.
    * 'cat todo.lst'
  * Display the content of a file using absolute path'
    * 'cat ~/Documents/todo.lst'
  * Display the content of a file with line numbers
    * 'cat -n ~/Documents/todo.md'

## cp
* Description
cp copies files/directories from a source to a destination

* Formula 
'cp + files + destination'

* Examples
  * To copy a file
    * 'cp Downloads/wallpapers.zip Pictures/'
  * To copy a directory with absolute path
    * 'cp -r ~/Downloads/wallpapers ~/Pictures/'
  * To copy the content of a directory to another directory
    * 'cp Downloads/wallpapers/* ~/Pictures/'
  
## cut
* Description
The cut command is used to extract a specific section of each line of a file and display it to the screen.

* Formula 
'cut + option + file(s)'

* Examples
  * Display a list of all the users in your system
    * 'cut -d ':' -f1 /etc/passwd'
  * Display a list of all the users in your system with their login shell
    * 'cut -d ':' -f1,7 /etc/passwd'
  * Cut a range of bytes per line
    * 'cut -b 1-5 usernames.txt'

## grep
* Description
Grep is used to search text in given file.

* Formula 
'grep + option + search criteria + file(s)'

* Examples
  * Search any line that contains the word "dracula in the given file:
    * 'grep 'dracula' ~/Documents/dracula.txt'
  * Search any line that contains the word contains the word 'dracula' regardless of the case.
    * 'grep -i 'dracula' ~/Documents/Books/dracula.txt'
  * Search any line that contains the word dracula regardless of case and with number line
    * 'grep -in 'dracula' ~/Documents/Books/dracula.txt'
   
## head
* Description
The head command displays the top N number of lines of a given files.

* Formula 
'head + option + file(s)'

* Examples
  * Display the first 10 lines of a file
    * 'head ~/Documents/Book/dracula.txt'
  * Display the first 5 lines of a file
    * 'head -5 ~/Documents/Book/dracula.txt'
  * Display the first 3 lines of a file
    * 'head -3 ~/Documents/Book/dracula.txt'

## ls
* Description
ls is used for listing the content of a given directory or the file/directory itself.

* Formula 
'ls + option + directory to list'

* Examples
  * List the content of the present working directory
    * 'ls'
  * List all the files inside the current working directory including hidden files.
    * 'ls -a'
  * List all the files inside a given directory
    * 'ls -a ~/Pictures'
  
## man
* Description
Man pages are documentation files that describe Linux shell commands, executable programs, system calls, special files, and so forth.

* Formula 
'man + command'

* Examples
  * Open the man page of the passwd command
    * 'man passwd'
  * Open a specific man page for the passwd command
    * 'man 5 passwd'
  * Show the man page section of the passwd command
    * 'man -f passwd'

## mkdir
* Description
mkdir is used for creating a single directory or multiple directories.

* Formula 
'mkdir + the name of the directory'

* Examples
  * Create a directory in the present working directory
    * 'mkdir wallpapers'
  * Create a directory in a different directory using relative path
    * 'mkdir wallpapers/ocean'
  * Create a directory in a different directory using absolute path
    * 'mkdir ~/wallpaper/forest'

## mv
* Description
Mv moves and renames directories.

* Formula 
'mv + source + destination'

* Examples
  * Move a file from a directory to another using relative path
    * 'mv Downloads/homework.pdf Documents/
  * Move a directory from one directory to another using absolute path
    * 'sudo mv ~/Downloads/theme /usr/share/themes'
  * Move multiple directories/files to a different directory
    * ' mv games/ wallpapers/ rockmusic/ /media/student/flashdrive/'

## tac
* Description
The tac command is used for displaying the content of a file in reverse order.

* Formula 
'tac + option + file(s) to display

* Examples
  * Display the content of a file located in the pwd
    * 'tac todo.md'
  * Display the content of a file using absolute path
    * 'tac ~/Documents/todo.md'
  * Display the contents of a file
    * 'tac example.txt'
  
## tail
* Description
The tail command displays the last N number of lines of a given file.

* Formula 
'tail + option + file'

* Examples
  * Display the last 10 lines of a file
    * 'tail ~/Documents/Book/dracula.txt'
  * Display the last 5 lines of a file
    * 'tail -5 ~/Documents/Book/dracula.txt'
  * Display the last 3 lines of file
    * 'tail -3 ~/Documents/Book/dracula.txt'

## touch
* Description
touch is used for creating files

* Formula 
'touch + file(s)'

* Examples
  * Create a file called list
    * 'touch list'
  * Create several files
    * 'touch list_of_cars.txt script.py names.csv'
  * Create a file using absolute path
    * 'touch ~/Downloads/games.txt'

## tr
* Description
The tr command is used for translating or deleting characters from standard output.

* Formula 
'Standard output | tr + option + set + set'

* Examples
  * Translate one character to another (For example a period with a comma.)
    * 'cat file.txt | tr '.' ',''
  * Translate white space into tabs.
    * 'cat program.py | tr "[:space:]" '\t'
  * Translate tabs into space.
    * 'cat file.py | tr -s "[:space:]" ' ''
  
## tree
* Description
The tree command is used to display the contents of a directory in a tree-like format.

* Formula 
'tree + directory'

* Examples
  * Display the contents of the current directory in a tree-like format
    *'tree'
  * Display the contents of a specific directory in a tree-like format
    * 'tree /path/to/directory'
  * Display the contents of a directory, including hidden files
    * 'tree -a /path/to/directory'

# Question 2

* How to work with multiple terminals open?
You can use keyboard shortcuts and use different colors and prompts to make terminals appear different. 

* How to work with manual pages?
To work with manual pages for a command or program simply use the man command follow by the name of the command or folder

* How to parse (search) for specific words in the manual page
To search for specific words in a manual page, you can use the "/" command followed by the word or phrase you want to search for.

* How to redirect output (> and |)
 The ">" symbol is used to redirect the output of a command to a file. For example, example, if you want to save the output of the "ls" command to a file called "file.txt", you would run: 'ls > file.txt
 The "|" symbol is used to pipe the output of one command to another. For example, if you want to list all the files in the current directory and sort them alphabetically, you would run: 'ls | sort'

* How to append the output of a command to a file
To append the output of a command to a file, you can use the ">>" symbol instead of the ">" symbol.

* How to use wildcards
Wildcard represents letters and characters used to specify a file name for searches. The (*) wildcard matches any number of characters and the (?) wildcard matches any single character.

* How to use brace expansion
You can use a brace expansion to create lists of file names, command line arguments, and more. You can also sue brace expansion with wildcards to generate more complex patterns.
