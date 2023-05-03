---
name: Anais Martinez
course: cis106
semester: spring 23
---

# Week report 6

## Wildcards.


### * Wildcard
the * wildcard matches from 0 to any number of characters.
* Examples:
  * List all the text file in a directory
    * 'ls *.txt'
  * List all the files that start with the word file
    * 'ls file*'
  * Copy all the mp4 files
    * 'cp Downloads/*.mp4 -/Videos/Movies/'

### ? Wildcard
The ? wildcard metacharacter matches precisely one character.
* Examples:
  * List all hidden files in the current directory
    * 'ls ./.??*'
  * List all the files that have a two character between letter b and k.
    * 'ls b??k*'
  * List all the files that have a 3 letter file extension
    * 'ls *.???'

### [] Wildcard
The [] wildcard match a single character in a range.
* Examples
  * Match all files that have a vowel after letter f.
    * 'ls f[aeiou]*'
  * Match all files that do not have a vowel after letter f.
    * 'ls f[!aeiou]*'
  * Match all files that have a range of letters after f.
    * 'ls f[a-z]*'

### Brace Expansion
Brace expansion {} is not a wildcard but another feature of bash that allows you to generate arbitrary strings to use with commands.
* Examples
  * To create a whole directory structure in a single command.
    * 'mkdir -p music/{jazz,rock}/{mp3files,videos,oggfiles}/new{1..3}'
  * To create a N number of files use.
    * 'touch website{1..5}.html'
  * Remove multiple files in a single directory.
    * 'rm -r {dir1,dir2,dir3,file.txt,file.py}'

## Practice
![Practice 5](../../labs/lab%205/practice5.png)
![Practice 6](../../labs/lab%205/practice6.png)
![Practice 7](../../labs/lab%205/practice7.png)
