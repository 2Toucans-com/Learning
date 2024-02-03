# 2Toucans Intern Resources

Maddie's WSL2 Local Dev Setup Guide: https://docs.google.com/document/d/1aGva9P2YBCb9cqcr6WqSrxxxfPq2GzboEcJF5gdnD0U/edit?usp=sharing

# Top Tips for Windows Users

## Easily open files with VSCode from your WSL2 terminal

Open VSCode.

Press ```Ctrl + Shift + P``` to open the Command Palette.

In the search box type "Shell Command" and look for the option ```Shell Command: Install "code"``` and run it. 

_If the option did not appear, then the VS Code configuration is already enabled on your PC._

Next open up your WSL2 (Ubuntu) terminal. 

Now you can open any file in the current directory with VSCode by typing ```code filename``` e.g. ```code README.md```. 

You can also type ```code .``` to open the current folder with VSCode


## Easily open directories with Windows Explorer from WSL2 terminal

In your WSL2 terminal you can simply type ```explorer.exe .``` to open the current directory with the Windows GUI. This can be helpful sometimes to just browse through folder structure, or rename things.