#                 
gitsave is an open source shell script for doing all the git things you need in one simple shell script. 
Reguarly you have to stage, commit, pull and push. Well the gitsave script does it all for you.

# Installation
the first command is to clone the repo. Make sure you have git installed for this step
go to terminal in mac os and linux. If you have windows that you might need a simulator for this
```
git clone https://github.com/iKittyCode/gitsave.git
```
Now you need to add the script to path. This command will depend on what shell you use but for now i'll do bash

first open your bash profile in a text editor. I will be using nano.
  
```
nano ~/.bashrc
```
then add the line

```
$PATH=$PATH:~/gitsave
```
This is if the directory is in the home directory


Now save the file and exit terminal
Once you exit reopen and type which gitsave.
If you get an output than that means it's working.
