#!/bin/bash

## Script Descriptions

### 0-iam_betty
- This script switches the current user to "betty" using the `su` command.

#### 1-who_am_i
- this script prints the effective username of the current user using `whoami` command

##### 2-groups
- this script prints all the groups the current user is part of using

###### 0-hello_world
- this scripts prints 'Hello, World' using `echo` command

###### 1-confused_smiley
-prints a script that displays a cconfused smiley using `echo "\"(Ôo)'` command
###### 11-directories 
- counts the number of directories and sub-directories in the current directory. (excluding ., ..) including hidden d using `find -mindepth 1 -type d | wc -l or `find . -type d ! -path '.'! -path './..'| wc -l
