# Shell Data Processing Assignment

## Bash

- ls - List items in current directory
```Bash
ls
ls -a
ls -l
ls -al
```
- cd - change directory
```Bash 
cd
cd ..
```
- cat - print contents of file to the window
```Bash
cat empty.txt
```
- curl - get source file from url
```Bash
curl "URL://www.GOESHERE.com" > output.txt
curl "http://shakespeare.mit.edu/hamlet/hamlet.5.2.html" > hamlet.txt
```
- touch - create a new file if one doesn't already exist
```Bash
touch new.txt
```
- mkdir - creates a new folder
```Bash
mkdir newFolder
```
- tr - Transform contents of a file
```Bash
tr 'start' 'end' < source.txt | sort 
tr ' ' '\12' < hamlet.txt | sort | uniq -c | sort -nr > result.txt
```
## PowerShell
- ni - creates an empty new item
```Powershell
 ni empty.txt
```
