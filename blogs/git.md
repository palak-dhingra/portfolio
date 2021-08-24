# common CLI commands

## list items

```shell
pwd
# it prints the current working directory 

ls
# it prints all files and directories in the current folder

ls -l
# it lists all files and directories with timestamp/size/access

ls -a
# shows hidden files and directories

clear
# clear the prompt

ls -al
# display all the files, hidden as well in a list manner

./ = current directory
../ = prev directory of current directory
````

## change directory
````shell
cd ./directory
# [change directory from ./ to ./directory]

cd ../
# [go 1 step backwards]

cd 
# [takes you to home directory]

cd ~
# [takes you to home directory]
````

## creating files & folders

````shell
mkdir CLI
# [make directory named CLI]

mkdir f1 f2 f3
# [creates 3 different folders]

mkdir -p f4/f5
# [create a folder f4 with sub folder f5]

touch file.txt
# [create a file named file.txt]

open file.txt
# [to edit the file.txt]
````

## remove files and folders
````shell
rm script.js
# [remove file name script.js]

rm f2/file.txt
# [remove file in a folder not in a current directory]

rmdir f1
# [remove directory f1]

rm -R f2
# [remove f2 folder with all its contents]
````

## copy and move
````shell
cp script.js f1/script.js

cp f4/index.html index.html
# [cp source destination]

cp -R f4 new
# [copy whole folder f4 into cwd and named as new]

mv index.html f1/index.html
# [move the file]

mv script.js hello.js
# [rename mv source destination: moved the same file from source to destination with different name]
````