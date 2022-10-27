# Welcome to Git
This README shows the steps to take to set up Git in your machine

## Install Git

### Check if git is insalled
The first step is to install git on your computer if you don't have it already, this can be verified by opening a terminal and runing the following
```bash
git -v
```
### If git is not installed 
Go to the following link:
https://git-scm.com/downloads

After the installer has been downloaded execute it and the default settings can be used, there is no need to modify them.

After having Git isntalled verify that it is insalled succesfuly using the git -v command

If you see something like 
```bash
git -v
git version 2.37.3.windows.1
``` 
Congratulations git has been succesfuly installed!!!

## Install Visual Studio Code 
If you don't have Visual Studio Code already installed go to the following link:
https://code.visualstudio.com/download

Download the installer for your operating system and install it.

## Create your first GitHub repo

Go to [GitHub](https://github.com/) and create a repo. In the left menue bar you will see a Recent Repositories section, next to that there is a green button that says 'New' click on it and fill in the required fileds. Once all the required fields have been populated press the green button that says 'Create repository'

Congratulations you created a GitHub repo!!!

## Clone GitHub repo to vscode

- Open VSCode 
- One the left menue bar selct the brach icon "source control"
- Click the blue 'Clone Repository' button
- You will see something pop up in the top of the VSCode window, if you see the "Clone from GitHub" option click on it. If not copy the URL for your GitHub repo
- You might be asked to log in to you GitHub account.
- Select the directory where you want the local repo to be housed

Congratulations you cloned a GitHub repo!!!

## Git commands
- git pull

  Pull the latest changes from remote reopo to local repo 
- git fetch

  Sync the latest changes from the remote repo
- git add

Stash a file to be commited
- git rm <file name>

  Remove a previoulsy stashed file from git
- git commit -m <your message>

  Commit latest stashed changes with <your message> message
- git push

  Push local commits to remote (GitHub) branch


