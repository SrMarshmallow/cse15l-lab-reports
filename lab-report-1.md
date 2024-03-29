# Lap Report 1

## Using the commands with no arguments:

**cd:**  ![Image](cd_noArgument2.png)
The working directory was ~/lecture1/messages. Using cd without any arguments does not cause any errors, but causes the command to return us to the home directory.

**ls:**  ![Image](ls_noArgs.png)
The working directory was the home directory. No other directories or folders such as messages showed up because those are in the lecture1 directory, but I was in the home directory which only contains the lecture1 folder that was listed. No errors were given.

**cat:**  ![Image](cat_noArgs.png)
There is no argument for the cat command to catenate, so no text is printed in the command line. However, you become unable to type or use other commands afterwards. Using Ctrl + C will exit you out of this state, and no errors are given despite the inability to type.

## Using the commands with a path to a directory as an argument:

**cd:**  ![Image](cd_DirectoryArg.png)
The working directory was ~/lecture1. Providing a directory as an argument gave the cd command a location to switch the working directory to. No errors were given.

**ls:**  ![Image](ls_DirectoryArg.png)
The working directory was the home directory. Because the lecture1 directory contains the files and folde in the picture, those were the ones listed when lecture1 was provided as an argument. No errors were given.

**cat:**  ![Image](cat_DirectoryArg.png)
The working directory was the home directory. Directories have no content to output themselves since they're intangible spaces that store other files. As a result, the command just tells us that the argument is a directory because the folder contains no other content. No errors were given

## Using the commands with a path to a file as an argument:

**cd:**  ![Image](cd_fileArg.png)
The working directory was ~/lecture1/messages. The cd command only works with directories, so providing a file as an argument instead provides an error telling us our argument is not a directory.

**ls:**  ![Image](ls_fileArg.png)
The working directory was ~/lecture1. A file cannot contain another file, so just providing one as an argument will cause it to list only itself. No errors were given.

**cat:**  ![Image](cat_fileArg.png)
The working directory was ~/lecture1/messages. "Hallow Welt!" appears in the terminal because the cat command is grabbing the contents of the txt file and outputting it as text in the terminal. No errors were given.
