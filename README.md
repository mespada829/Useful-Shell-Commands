## Useful-Shell-Commands :fire:

**Tools**: https://explainshell.com/

This is just a small collection of useful shell commands by category.

### General commands that can be used daily

```
man - Will print out a useful manual

echo $USER - To find your user path 

pwd - Print working directory to identify what path you are in

mkdir - Make a directory

cd - Change working directory

cd .. - Means the directory above the current one

ls - Will list what files you have in folder

ls -a - Will display hidden files

touch - Make a file 

cp - Copy a file 

rm - Remove a file

find - find a file quick

cat - Inputs contents of a file

history - display your command history

grep - Selects lines in files that match patterns

locate - Will track where a file is 

zip -r - (new name.zip dirname) - Zip a directory

open . - To open that particular directory in a GUI

Ctrl-R - Search through the previously entered commands

Ctrl-C - Opens a new command line in the same window

cp -R (folder name) to cope over 

exit - Close the terminal

```

### Transfer a files 

```
scp - Secure file copy from or to machine

command > file -  Redirects a command’s output to a file

```

### Commands for printing from your default printer

```
lpr file.ps - Print in default printer

lpq - Show printer jobs in queue 

```

### Editors 

```
nano -  Simple terminal-based text editor.

vim - Highly configurable text editor built 

```

### Users, permissions etc

```
who -a - List all users that have logged in recently

uptime - Show how long the system's been running

w - Who is logged in

```

### Making an alias 

```
Remember to cd to your profile. This depends on the shell you are using. I use ZSH so I nano into .zshrc file

alias peaceout="exit"; - This alias would close the terminal since peaceout is a short for that command

```

### Additional cool things to do

```
You may add an emoji or customize your command line if you cd into `~/.oh-my-zsh/themes` and nano into your theme. 
For bash users this link my help - https://medium.com/@joshuaxavier/how-to-customise-your-command-prompt-to-include-an-emoji-647e1f3e4027
```

### SSH into another computer

```
Go to settings > Sharing > Enable Remote Login > Click on the + sign to add yourself and / or other users.
On the top you will find -> To log in to this computer remotely, type “ssh etc"
```

