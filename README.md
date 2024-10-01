# Git-and-Github
This  repository is a comprehensive collection of essential Git and GitHub commands, designed as a quick reference guide for efficient version control and collaboration, making it easier to manage projects and workflows.

## Basic Git Command 
- To check version of git <code>git --version</code>
- To check current working directoory <code>pwd</code>
- To check  all filles and folders in current working directoory <code>ls</code>
- Clear window <code>clear</code>
<br>

## Configuring Git

Git configuring means setting up Git to work the way you want. You do this by setting your name, email, and other preferences. Some important commands are:

### 1-Set your name and email (for identifying commits):
<code>git config --global user.name "Your Name"</code> <br>
<code>git config --global user.email "youremail@example.com"</code>

### 2- Check your settings:
<code>git config --list
</code>

## Clone and Status

### Local vs Remote in Version Control

- LOCAL refers to the copy of the project stored on your computer or laptop. You can make changes here, create commits, and track your work.

- REMOTE refers to a version of the project stored on a server (like GitHub). It's shared with others, allowing you to collaborate and back up your work.

 You push changes from your local version to the remote and pull updates from the remote to your local. 

 ### Clone and Status

 - CLONE : Cloning a repository to your locall machine.
     <code>git clone <-some link-> </code>

 - STATUS : Displays the state of the code
   <code>git status</code>

### Terminal Commands
   <br>
- <code>cd</code> Command to change directory => want to  go from outer folder to inner.
- Tab : Press tab to  auto  complete.
- <code>Clear</code> this command clear the terminal.
- <code>ls</code> ls(List Files) command list all files and folders.
- <code>ls -a</code> to see all files including hidden files.
  <br>
PowerShell doesn't recognize <code>ls -a</code> in the same way as other shells like Bash. In PowerShell, <code>ls</code> is an alias for <code>Get-ChildItem</code>, and the <code>-a</code> flag is ambiguous because there are multiple parameters starting with "a".
<br>
To list all files, including hidden ones, in PowerShell, you can use:<br>
<code>ls -Force</code>
<br>Or<br>
<code>Get-ChildItem -Force</code>
  <br>
### Git Status
  <br>
- UNTRACKED: new files that  git  doesn't yet track.
- MODIFIED: changed
- STAGED: File is ready to be committed
- UNMODIFIED: Unchanged

