# Using remote access with ieng6

## Installing VS Code
In order to access ieng6, I needed to download Visual Studio Code. I went onto the website for [Visual Studio Code](https://code.visualstudio.com/) to download and install the program, which went rather smoothly. 

![Image](Screenshot 2023-04-10 102819.png)

I also needed to download git to set my default terminal as a Git Bash terminal. To do this, I first installed git from [GitforWindows](https://gitforwindows.org). 

After installing git, I opened up Visual Studio Code, opened the terminal with "Ctrl + `", opened the Command Palette with "Ctrl + Shift + P", and chose Git Bash as the default terminal. 

## Remotely Connecting
To remotely connect, I input the following:
```
$ ssh cs15lwi23en@ieng6.ucsd.edu
```

After that, I was prompted to insert my password, which I input, allowing me onto the remote server. I did not input my password correctly for the first time, and it shows in the information that was given:

![Image](Screenshot 2023-04-10 102915.png)

## Running Commands

After accessing the remote server, I ran several commands, such as ```$ pwd```, which printed the path to the working directory.

![Image](pwd.png)

```$ ls -a```, which listed all the files in the directory, including hidden files. 

![Image](ls -a.png)

```$ mkdir Hello Everyone```, which created new directories called Hello and Everyone

![Image](mkdir hello everyone.png)

```$ cat /home/linux/ieng6/cs15lsp23/public/hello.txt```, which listed the contents of the file "hello.txt".

![Image](cat.png)

I attempted to list the files in another person's directory using ```$ls /home/linux/ieng6/cs15lsp23/cs15lsp23fk```, but I was denied access.

![Image](Screenshot 2023-04-10 102947.png)
