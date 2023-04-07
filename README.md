# Pipex

The purpose of this project is the discovery in detail UNIX mechanism - **pipe**
 
# Usage

To compile, use **make**, **make all** or **make bonus**.</br>
The program pipex should repeat the behaviour of the next shell command
```
make
```
```
$> < file1 cmd1 | cmd2 > file2
```
and looks like this:

```
$> ./pipex file1 cmd1 cmd2 file2
```
All errors like: wrong commands, permission to files and etc, need be handle.

# Example
```
 ./pipex infile "ls -l" "wc -l" outfile
 ```
