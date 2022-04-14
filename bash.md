# Bash command

- [Bash command](#bash-command)
  - [bash](#bash)
  - [clear](#clear)
  - [pwd](#pwd)
  - [cd](#cd)
  - [cp](#cp)
  - [dir](#dir)
  - [exit](#exit)
  - [ls](#ls)
  - [mkdir](#mkdir)
  - [mv](#mv)
  - [rm](#rm)
  - [touch](#touch)

## bash

**bash** is used to execute bash commands.

```bash
bash
```

## clear

**clear** is used to clear the terminal.

```bash
clear
```

## pwd

> pwd
> : print working directory

**pwd** is used to print the current working directory.

```bash
pwd
```

## cd

> cd
> : change directory

**cd** is used to change the current working directory. cd can be used in two different ways as follows:

going inside the folder:

```cmd
cd main/sub
```

going to parent directory:

```cmd
cd ..
```

## cp

> cp
> : copy

**cp** is used to copy files.

```bash
cp <source> <destination>
cp demo.txt main/sub
```

## dir

> dir
> : directory

**dir** is used to list the files and folders in the current working directory.

```bash
dir
```

## exit

**exit** is used to exit the terminal.

```bash
exit
```

## ls

> ls
> : list

**ls** is used to list the files and folders in the current working directory.

```bash
ls
```

## mkdir

> mkdir
> : make directory

**mkdir** is used to create a new directory.

```bash
mkdir <directory>
mkdir main
```

## mv

> mv
> : move or rename

**mv** is used to move or rename files.

```bash
mv <source> <destination>
mv demo.txt main/sub
```

```bash
mv <current_name> <new_name>
mv demo.txt demo_renamed.txt
```

## rm

> rm
> : remove

**rm** is used to remove files. rm is used in two different ways as follows:

1. remove a file
2. remove a directory

```bash
rm <file>
rm demo.txt
```

```bash
rm -rf <directory>
rm -rf main
```

## touch

**touch** is used to create a new file.

```bash
touch <file>
touch demo.txt
```
