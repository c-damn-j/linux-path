# linux-path
Add your scripts folder to the PATH in order to run your scripts from anywhere

# What is this?
Running Bash scripts in Linux could be painful.
Everytime you want to run a script you made, you have to cd to the script's location and run in from there.
This simple command helps you running your scripts from whereever location you are.

```
echo 'export PATH="$PATH:<Your Folders Locations>"' >> $HOME/.bashrc
```
```
. $HOME/.bashrc
