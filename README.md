# Git and GitHub
This repository is a comprehensive collection of essential Git and GitHub commands, designed as a quick reference guide for efficient version control and collaboration, making it easier to manage projects and workflows.

---

## Basic Git Commands
- **Check Git version**: 
  <code>git --version</code>
  - Displays the current version of Git installed.

- **Check current working directory**: 
  <code>pwd</code>
  - Shows the path of the directory you are currently in.

- **List all files and folders**: 
  <code>ls</code>
  - Lists files and folders in the current directory.

- **Clear terminal window**: 
  <code>clear</code>
  - Clears the terminal screen for a fresh view.

---

## Configuring Git
Configuring Git means setting your preferences, like your name and email.

### Set your name and email:
- **Set your name**: 
  <code>git config --global user.name "Your Name"</code>
  
- **Set your email**: 
  <code>git config --global user.email "youremail@example.com"</code>
  
### Check your settings:
- **List current configuration**: 
  <code>git config --list</code>
  - Displays your current Git configuration settings.

---

## Understanding Local and Remote Repositories
- **Local**: Your personal copy of the project on your computer.
- **Remote**: A version of the project stored on a server (like GitHub) for sharing and collaboration.

### Clone and Status
- **Clone a repository**: 
  <code>git clone &lt;some link&gt;</code>
  - Creates a local copy of a remote repository.

- **Check repository status**: 
  <code>git status</code>
  - Displays the current status of files in the working directory.

### Terminal Commands
- **Change directory**: 
  <code>cd</code> 
  - Navigate into a specific directory.
  
- **Go to previous folder**: 
  <code>cd ..</code> 
  - Move up one directory level.
  
- **Auto-complete**: 
  - Press **Tab** to auto-complete file and directory names.

- **List files**: 
  <code>ls</code> 
  - Show files in the current directory.

- **List all files (including hidden)**: 
  <code>ls -a</code>
  - Show all files, including hidden ones.

- **Make a new directory**: 
  <code>mkdir</code>
  - Create a new folder.

- **PowerShell alternative for listing all files**: 
  <code>ls -Force</code> or <code>Get-ChildItem -Force</code>

### Git Status Indicators
- **UNTRACKED**: New files not yet tracked by Git.
- **MODIFIED**: Files that have been changed.
- **STAGED**: Files ready to be committed.
- **UNMODIFIED**: Files that have not changed.

---

## Add and Commit Changes
- **Add files to staging**: 
  <code>git add &lt;file name&gt;</code>
  - Stages a specific file for commit.
  
- **Stage all changes**: 
  <code>git add .</code>
  - Stages all modified and untracked files.

- **Commit changes**: 
  <code>git commit -m "meaningful message about update"</code>
  - Records changes with a descriptive message.

---

## Push Command
- **Upload changes to remote**: 
  <code>git push origin main</code>
  - Pushes local changes to the `main` branch of the remote repository.

---

## Setting Up and Managing a Git Repository
- **Initialize a new Git repository**: 
  <code>git init</code>
  - Creates a new empty Git repository.

- **Add a remote repository**: 
  <code>git remote add origin &lt;link&gt;</code>
  - Links your local repository to a remote repository (default name is `origin`).

- **Verify remote repository URLs**: 
  <code>git remote -v</code>
  - Lists the remote URLs for push and pull operations.

- **Check current branch**: 
  <code>git branch</code>
  - Displays the current branch you are working on.

- **Rename the current branch to 'main'**: 
  <code>git branch -M main</code>
  - Renames the active branch to `main`.

- **Push changes to the remote branch**: 
  <code>git push origin main</code>
  - Sends your local changes to the `main` branch of the remote repository.

- **Push and set upstream branch**: 
  <code>git push -u origin main</code>
  - Pushes to the `main` branch and sets it as the default upstream for future pushes.

---

## What is a Branch?
A **branch** in Git is a separate version of your project where you can make changes without affecting the main code.

### Definition:
A branch allows you to work on different features or fixes independently. Once you're done, you can merge your changes back into the main branch.

### Key Points:
- **Isolation**: Changes in one branch don’t impact others.
- **Collaboration**: Multiple people can work on different branches at the same time.
- **Version Control**: You can track and combine changes easily.

### Branch Commands

- To check branch: <code>git branch</code>
- To rename branch: <code>git branch -M <-Name-></code>
- To navigate: <code>git checkout <-branch Name-></code>
- To create new branch : <code>>git checkout  -b <-branch Name-></code>
- To delete branch : <code>git branch -d <-branch Name-></code>

### Merging Code 

#### Way 1

- <code>git diff <- branch name -></code>  To compare commits,branches,files & more
- <code>git merge <- branch name -></code>  To merge two branches

#### Way 2

- Create a Pull Request (PR)

  ##### Pull Request
 It lets you tell other about changes you have pushed to a branch in a repositor on a Github.

 #### Pull COmmand

 Pull command used to fetch and download  content from remote repo and immediately update the local repo to match that content.

 <code>git pull origin main</code>

 ---

## Resolving Merge Conflicts

An event that taes place when Git is unable to automatically resolve differnce in code between two commits.

---

