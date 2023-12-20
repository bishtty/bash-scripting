# bash-scripting

_echo_ is command “********aayush”******** is arguement.

![image](https://github.com/bishtty/bash-scripting/assets/42225594/90dbbe20-d0da-4149-b003-7912afd49eef)

### using vim text editor

`*vim textfile.txt`* create a text file

`i` (write the character b4 the cursor) to get into insert mode, now put text in file

`a` (write the character after the cursor)

************note: press `escape` button then give these : command*

`:w` to save the written stuff in file

`:q` to exit from vim editor

`:wq` to directly save and exit

`:q!` to ignore the change made in file and exit

-**************to make a bash file: `vim FILENAME.sh`*

***********-after your have written your bash script change the permission: `chmod u+x FILENAME.sh`*

-**********************then to run bash file:********************** *************`./FILENAME.sh`*************

### writing first shell script

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/e44254cb-7cb8-45ed-9203-8289fc9552f5/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/b4546217-e3f9-4551-8cf5-318b18416bcf/Untitled.png)

## variables

making another shell file, to echo first name and last name

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/a0b66b3e-97e6-4978-80a4-4f20e7090c02/Untitled.png)

this is thing which i put inside vim editor

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/58d80e57-61b4-4ee4-9af8-7a3c6ab848f8/Untitled.png)

making interactive bash script

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/d794df32-5ed0-43cd-8df3-a195f65e3b24/Untitled.png)

inside vim editor

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/df23c4fe-c2e6-460e-bab6-a894a164baaa/Untitled.png)

## positional arguement

arguements are a specific positions- commands can take in arguements at a specific position, counting from 1(o being reserved for the shell)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/cc5dac2f-b8c4-44e3-8af7-02d17a7e4ce7/Untitled.png)

create bash script to print first name and last name with just one line of code

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/2902b71c-4fa1-4e7b-a5db-e1e2ab14764d/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/765d24aa-27da-4f5c-9b94-048dbe590c2a/Untitled.png)

## output/input redirection

- pipe

output redirection symbol used

>symbol to write to a file

>>to append to a file

used in- logging to a logfile (for e.x using timestamps), dynamically creating a (config) files

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/aa7d562a-84ab-4358-b2f5-4b3411874b17/Untitled.png)

****************good day to you****************  replaced ************hello world************  because `>` using this replaces the previous written data

below showing `>>` example

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/d0379950-c059-4563-9a5e-750c54032aaa/Untitled.png)

`wc` command for word count

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/ae3ccf1b-e79b-44dc-8e93-96c9bf0772f8/Untitled.png)

*********************notice the difference*********************

`EOF` command

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/a4260c25-bf5d-4b43-a0bc-acb988d5d788/Untitled.png)

## test operator

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/ac412634-8c83-46e1-bce6-d831ee20e5c5/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/870e3890-1f86-4e23-a7de-8498be9371f7/Untitled.png)

## if/elif/else

********************actual code(running)********************

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/d191e968-9b7b-4ebe-ba5d-6b4aee0edfbb/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/954e17db-1ef2-4bba-ab38-ff87a51d505e/Untitled.png)

********my code(not running; error: “bad susbtitution”)********

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/35b15cb5-ce3c-48f2-a20e-8ed70ff868c8/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/8bbaf92c-3212-4bca-a63c-488986843a7a/Untitled.png)

*******************************my code now running- i changed #!/usr/bin/zsh to **********************#!/bin/bash***********************

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/90e01181-5184-4d88-8a36-d9c1bc302377/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/0e7aa280-339e-49d0-8859-3c8c7f130f3e/Untitled.png)

## case statements

-better then if-elif-else when

-checking for multiple values

-easier to read

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/0ce03a6d-af84-4d29-814b-a7ed612581f2/Untitled.png)

here `*` is used catch-all or default option

## Arrays

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/45b237d8-a3b4-4375-8efe-ffb74b723b4f/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/f26a5f22-ea13-49db-8772-e2fc19214577/Untitled.png)

## for loop

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/64d77e8f-eeea-4051-ae64-180b9d15cd96/Untitled.png)

## functions

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/6386194d-e974-44bb-a9a5-1bbcc55b3117/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/fd7f0c60-873d-4b90-b65f-50a5f07c4c16/Untitled.png)

**********local and global variable**********

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/e83ca020-a3d3-4e25-be12-2dfb909a5eae/Untitled.png)

here we have defined global and local variable of same name and local variable have overwritten the 2nd echo command of global variable with its output

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/7365e9c2-14c0-4671-b5e6-b32e3fbf644d/Untitled.png)

to avoid this we explicitly define local variable by using ******local****** keyword

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/734cfac2-a10b-42aa-8684-8b4e2482ca23/Untitled.png)

now check the how output is changed

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/395ff10f-cf55-46c3-bc00-11ac74f875b9/Untitled.png)

## exit codes

**************************************positional function**************************************

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/1640eafe-235f-4f7c-b914-d39c96c7b439/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/55fd3f87-cca4-47aa-982f-74243502073a/Untitled.png)

## awk

to fillter file content or output of the command in such a way that we can print out the most essential parts and get the output the way we like it.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/d2d86c0e-6988-48c1-a752-0de542e8e353/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/d7df1441-7eae-48c6-9a06-bd3ab8d59b8e/Untitled.png)

## SED

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/872d9749-e859-4476-b810-650706cd242f/aa81bf96-c2e3-4f91-a133-27451deb7d3a/Untitled.png)

understanding the **sed** command

`sed 's/fly/grasshopper/g' sedtext.txt`

here `s` is used to substitute; fly with grasshopper; `g` is to change globally
