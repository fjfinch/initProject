# initProject
This script will create projects (folders) within a workspace. The workspace that initially will be created is called 'Git' (for users in: `/$HOME/Desktop/Git/`, for root in: `/root/Git/`)

By giving a file as an argument, it will create a project (folder), with the same name as the file, in the workspace.

Then it will move the file into the folder, and initialize a Git repository.

Additionally it will give a SymLink command for if you want to create a SymLink in $PATH (/usr/local/bin/)

## Context
I just wanted to make/start easy projects. All stored in one place, with a git repository.. That's it.

## How to use?
This scipt is made on/for (Debian) Kali Linux.

Usage: `initProject <FILE>`

where \<FILE\> is the script you want to be stored in the workspace, and with a initialised git rep.
