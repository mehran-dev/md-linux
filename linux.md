openSUSE linux like windows

##simple commands

```
data
cal =>calendar
cal y
cal 1990
clear
exit
```

##folder in linux refers to directory

```top most dir = /
bin => binary  executable commands
opt => optional => commercial programs Nnot defaaults like chrome
home =>
temp =>
var => variable data lock files user data bases
```

current .
parent ..

##Navigate

```
pwd => print current directory
ls => list directory content
cd



```

soft link => shortcuts
hard link =>

ls commands

```
ls -i -a -t -r -l

```

~~END OF PART ONE~~

command

```
touch
mkdir
rmdir
rm
rm -R
rm -i  => prompt before any file -i=interactive
rm -f

cp x y

cp x destination=dir2 y

cp -v => verbose

mv  //rename or move


file your_file_name

```

~~END OF PART TWO~~

view edit => GEDIT

**^G= control + g **

history

```
cat => catinate
tac

head file1

wc // line  word   byte/char



```

##types of commands

```
(1) Executable programs  => usr bin dir => e.g:cp
(2) Shell builtins  => bash
(3) Shell scripts  e.g: cd
(4) Alias => define your self

type cmdname

which

man cp
man ls
man cd

whatis cp  //explains cp
whatis date



```

#build your commands

```
cmd ; cmd ; cmd

cmd && cmd && cmd


```

wildcard

```
*
? match single char


cp * dir1

mv file* dir1 // file1.txt ,....
mv file?.txt dir1 // file1.txt ,.... JUST a single charector

[range]
cp [abc]* , axewfwef, bwefwef, cwefih

cp [!abc]* , anything but a,b,c 

cp [[:upper:]]*  // Just Uppercase 

```



Alias 


```
alias newcmd = "cp . .. ; next cmd ; next cmd   "

```