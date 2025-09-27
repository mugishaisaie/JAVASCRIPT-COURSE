

# Git and GitHub Lesson

## What is Git?


● Version Control System
○ Keep careful track of changes in your files
○ Collaborate with others on your projects more easily
○ Test changes without losing the original versions
○ Revert back to older versions when/if needed
● GitHub: web-based hosting service for git
○ Provides a "remote" location for storing your git workspaces
○ Useful if you lose/break your computer, etc.



 ## Git Configure

 1. configure the Name Git will use
   -> git config --global user.name "userName"
 2. Configure The Email Git will use:
 git config --global user.email "userEmail"


 ## Some Git Commands 

 - LS -a : List All directory even hidden ones
 - LS :  it List all directory files and folders
 - Start . : will Open File Explorer
 - LS Document/ : This will Return All folders and files from the Document
 - PWD: Print Working Directory (Where you're working In)
 - CD : Change Directory
 - CD .. : Change Directory Back
 - touch: use touch to create a file 
 - mkdir : Will Create a New Directory
 - rm index.js : rm will delete file permanently
 - rm -rf: rm -rf  used to delete directory/folder


## Mostly Used Commands are:
* Git Init : initialize repository and create Repository
* Git Status: Gives information on the current Status of Git Repository
NB: Before Running Git Init , Use Git Status to verify that you're not currently inside the Repository
* Git Add .: to add Files to the Staging Area
* Git Commit -m "message" : to commit all staged changes with a message

## Ignoring Files
we can tell Git which files or directories to ignore in a given repository using a .gitignore file

Examples of Some Files we can ignore are:
- Secrets
- API Keys
- Credentials
- operating system files
- Node Modules files



## FULL PROCESS TO PUSH CODE TO GITHUB
1. Initialize a Local Repository

If you already have a project on your computer:

- git init

- git add .
- git commit -m "Initial commit"

2. Connect to GitHub & Push Code

Create a repo on GitHub (without README if you already have one locally).

Link your local repo to GitHub:
- git remote add origin url
- git branch -M main       # Rename master → main (GitHub uses main by default)
- git push -u origin main  # Push to GitHub and set tracking



## PULL CODE FROM GITHUB

 Clone a Repository (Download from GitHub)
 - git clone URL : This gives you a local copy connected to the remote.
 - git pull origin main


##  Working with Branches 

Branches allow you to work on features without breaking the main code.

Create a new branch
- git checkout -b feature-login

Switch branches
- git checkout main
Push a branch to GitHub
- git push -u origin feature-login
See branches:

- git branch -a







