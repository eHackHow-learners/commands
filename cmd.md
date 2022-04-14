# CMD

Description:

- [CMD](#cmd)
  - [cmd](#cmd-1)
  - [cls](#cls)
  - [cd](#cd)
  - [copy](#copy)
  - [robocopy](#robocopy)
  - [del](#del)
  - [dir](#dir)
  - [exit](#exit)
  - [md](#md)
  - [mkdir](#mkdir)
  - [rd](#rd)
  - [rmdir](#rmdir)
  - [start](#start)
  - [shutdown](#shutdown)
  - [tree](#tree)
  - [type](#type)

## cmd

> cmd
> : command prompt

**cmd** is used to execute a command prompt as terminal.

```cmd
cmd
```

## cls

> cls
> : clear screen

**cls** command is used to clear the screen.

```cmd
cls
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

## copy

**copy** is used to copy the file or folder to another location.

```cmd
copy <source> <destination>
copy demo.txt main/sub
```

## robocopy

**robocopy** is another and advanced way to copy files and folders.

```cmd
robocopy /s /e <source> <destination>
robocopy /s /e demo.txt main/sub
```

## del

> del
> : delete

**del** is used to delete the files.

```cmd
del <file>
del demo.txt
```

## dir

> dir
> : directory

**dir** is used to list the files and folders in the current working directory.

```cmd
dir
```

## exit

**exit** is used to exit the command prompt.

```cmd
exit
```

## md

> md
> : make directory

**md** is used to make a new directory.

```cmd
md <directory>
md demo_folder
```

## mkdir

> mkdir
> : make directory

**mkdir** is used to make a new directory.

```cmd
mkdir <directory>
mkdir demo_folder
```

## rd

> rd
> : remove directory

**rd** is used to remove the directory.

```cmd
rd <directory>
rd demo_folder
```

## rmdir

> rmdir
> : remove directory

**rmdir** is used to remove the directory.

```cmd
rmdir <directory>
rmdir demo_folder
```

## start

**start** is used to start a new command prompt.

```cmd
start
```

## shutdown

**shutdown** is used to shutdown the computer.

```cmd
shutdown -s -t 10
```

## tree

**tree** is used to list the files and folders in the current working directory.

```cmd
tree
```

## type

**type** is used to create file or duplicate a file.

Crate blank file:

```cmd
type nul > demo.txt
```

Crete duplicate file:

```cmd
type demo.txt > demo_copy.txt
```
