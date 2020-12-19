# initProject
1) (first use) It will create a folder: a workspace (if there isn't one already). The workspace will be called 'Git' (for users: `/$HOME/Desktop/Git/`, and for root: `/root/Git/`)
2) Then it takes the given input, a script, and creates a folder within the workspace: a project. This folder will take the name of the given script.
3) It will move the given script into the new project.
4) It will initialize a Git repository for this project.
5) Additionally if you want to create a SymLink of the file in PATH ('/usr/local/bin/'), it will output the correct command.

## Context
I just wanted to make / start easy projects with bash. All stored in one place, with a Git repository.. That's it.

## How to use?
This script is made on / for (Debian) Kali Linux.

Usage: `initProject <FILE>`

where \<FILE\> is the script you want to be stored in the workspace, with a initialized git repository.
