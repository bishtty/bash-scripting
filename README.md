# bash-scripting

_echo_ is command “********aayush”******** is arguement.

![image](https://github.com/bishtty/bash-scripting/assets/42225594/90dbbe20-d0da-4149-b003-7912afd49eef)

### using vim text editor

`*vim textfile.txt`* create a text file

`i` (write the character b4 the cursor) to get into insert mode, now put text in file

`a` (write the character after the cursor)

*note: press `escape` button then give these : command*

`:w` to save the written stuff in file

`:q` to exit from vim editor

`:wq` to directly save and exit

`:q!` to ignore the change made in file and exit

-*to make a bash file: `vim FILENAME.sh`*

*-after your have written your bash script change the permission: `chmod u+x FILENAME.sh`*

-**********************then to run bash file:********************** *************`./FILENAME.sh`*************

### writing first shell script

![image](https://github.com/bishtty/bash-scripting/assets/42225594/22453c7e-f674-4e4d-96ae-6b3379d5f3da)


![image](https://github.com/bishtty/bash-scripting/assets/42225594/157b0ff1-5c4b-402e-97b1-5b54fae94fa3)


## variables

making another shell file, to echo first name and last name

![image](https://github.com/bishtty/bash-scripting/assets/42225594/be5d6b7a-f347-4eae-bfdb-96c8b98e60f2)


this is thing which i put inside vim editor

![image](https://github.com/bishtty/bash-scripting/assets/42225594/c9762377-651b-4581-94fe-68353d544a1e)


making interactive bash script

![image](https://github.com/bishtty/bash-scripting/assets/42225594/e3cb14b8-11f0-4997-935f-2131023e8fa0)


inside vim editor

![image](https://github.com/bishtty/bash-scripting/assets/42225594/1b4d9f2e-e070-42d3-82a1-49898a5426c3)


## positional arguement

arguements are a specific positions- commands can take in arguements at a specific position, counting from 1(o being reserved for the shell)

![image](https://github.com/bishtty/bash-scripting/assets/42225594/c6dfa3f5-e7ac-4cb4-aa4a-1992ae2e1019)


create bash script to print first name and last name with just one line of code

![image](https://github.com/bishtty/bash-scripting/assets/42225594/11cc1a24-28e1-49bd-8acd-6aae7af6afbe)


![image](https://github.com/bishtty/bash-scripting/assets/42225594/e0b99722-7ba8-4a04-b1d1-8d137fa383b2)


## output/input redirection

- pipe

output redirection symbol used

`>` symbol to write to a file

`>>` to append to a file

used in- logging to a logfile (for e.x using timestamps), dynamically creating a (config) files

![image](https://github.com/bishtty/bash-scripting/assets/42225594/8f975272-498e-413b-a271-dfe2a65c01f0)


****************good day to you****************  replaced ************hello world************  because `>` using this replaces the previous written data

below showing `>>` example

![image](https://github.com/bishtty/bash-scripting/assets/42225594/1375db3a-a623-4688-8257-006461c43507)


`wc` command for word count

![image](https://github.com/bishtty/bash-scripting/assets/42225594/0e509b21-26d2-4577-89b9-b881fb9bca0a)

*********************notice the difference*********************

`EOF` command

![image](https://github.com/bishtty/bash-scripting/assets/42225594/3a9ed166-2eca-4d68-94cc-4480883619f7)


## test operator

![image](https://github.com/bishtty/bash-scripting/assets/42225594/0159f85a-2a79-43b4-a527-d473eca6014c)


![image](https://github.com/bishtty/bash-scripting/assets/42225594/0018b4db-33e5-4ee5-b03a-1888416ed030)


## if/elif/else

********************actual code(running)********************

![image](https://github.com/bishtty/bash-scripting/assets/42225594/28b2cd79-f498-49bf-89b8-773719b3592f)


![image](https://github.com/bishtty/bash-scripting/assets/42225594/b21b285b-dccd-41ae-ac0a-713511a44e61)


********my code(not running; error: “bad susbtitution”)********

![image](https://github.com/bishtty/bash-scripting/assets/42225594/7f43bac7-920d-4b7f-bd7e-0280eb8c6189)


![image](https://github.com/bishtty/bash-scripting/assets/42225594/3b33cdf5-0f82-4ba6-8eac-b40843d48766)


*******************************my code now running- i changed #!/usr/bin/zsh to **********************#!/bin/bash***********************

![image](https://github.com/bishtty/bash-scripting/assets/42225594/0026c969-3f63-4cea-b4ab-6b812af76ffc)


![image](https://github.com/bishtty/bash-scripting/assets/42225594/51f0bc81-88fd-4c7b-8eaf-46fa49b5ab15)


## case statements

-better then if-elif-else when

-checking for multiple values

-easier to read

![image](https://github.com/bishtty/bash-scripting/assets/42225594/4fa24a9c-471a-4942-a8dd-a60c6bc49ab4)


here `*` is used catch-all or default option

## Arrays

![image](https://github.com/bishtty/bash-scripting/assets/42225594/e8f5cf54-9793-4dcb-b84d-ccd14f6d2e1a)


![image](https://github.com/bishtty/bash-scripting/assets/42225594/87f69181-12d6-42a7-9aaf-a99d12ce9b16)


## for loop

![image](https://github.com/bishtty/bash-scripting/assets/42225594/c2148d4e-1ae8-44c5-b71a-2aeb5be316b7)


## functions

![image](https://github.com/bishtty/bash-scripting/assets/42225594/baa27953-7edc-4fb8-92a7-b8ba4878501c)


![image](https://github.com/bishtty/bash-scripting/assets/42225594/da7ceb16-bf9e-43d8-9fd4-990cb18a2c3e)


**********local and global variable**********

![image](https://github.com/bishtty/bash-scripting/assets/42225594/fbd3458e-da2b-422f-ad60-70f8f63da052)


here we have defined global and local variable of same name and local variable have overwritten the 2nd echo command of global variable with its output

![image](https://github.com/bishtty/bash-scripting/assets/42225594/1883e23c-3789-4769-98be-c08db6698173)


to avoid this we explicitly define local variable by using ******local****** keyword

![image](https://github.com/bishtty/bash-scripting/assets/42225594/fc992674-e5d4-400d-bcda-57c8e95cf008)


now check the how output is changed

![image](https://github.com/bishtty/bash-scripting/assets/42225594/4475e11c-b50b-4faf-b03d-b8aa63deff57)


## exit codes

**************************************positional function**************************************

![image](https://github.com/bishtty/bash-scripting/assets/42225594/c9ed3bf7-e141-4c5d-ab03-b193d8385bd4)


![image](https://github.com/bishtty/bash-scripting/assets/42225594/ca0b878e-6e61-4ab8-b017-eb586bb63c6d)


## awk

to fillter file content or output of the command in such a way that we can print out the most essential parts and get the output the way we like it.

![image](https://github.com/bishtty/bash-scripting/assets/42225594/76eb8b0e-08bc-4820-9d0a-cf29e0402eea)


![image](https://github.com/bishtty/bash-scripting/assets/42225594/3e017912-cea9-4036-a594-58b462efaecb)


## SED

![image](https://github.com/bishtty/bash-scripting/assets/42225594/cd04a1fc-0004-42d1-81bb-cdbe66a63a64)


understanding the **sed** command

`sed 's/fly/grasshopper/g' sedtext.txt`

here `s` is used to substitute _fly_ with _grasshopper_ `g` is to change globally
