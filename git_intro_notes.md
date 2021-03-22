# Git

## What is git?
- Git is a "distributed version control system"
- Git is a permanent record w/ a time machine (and parallel universe component)
- think about updates and software versions
    - version 1.0 is still running, people still use it
    - version 1.1 is still running...
    - version 1.1.1 fixes a little bug, people still use it
    - version 1.2 
    - version 2.0
    - these are all different versions of software
- distributed = runs on many computers, example: GitHub and your laptop
- github is like dropbox for code

## So what?
- we need to save our changes
- we need to save a record of what changed, when, and why
- we need the ability to travel in time to save points
- See the differences in code between v2.0 and version 2.1
- We already have a version control system:
    - have you ever saved resume.pdf and saved on desktop
    - how about resume_final.pdf and saved to your desktop?
    - how about resume_finalFINAL.pdf?
    - resume_forCodeupMondayInterview.pdf
    - limits of this: all the data and meta data is in the filename
- Version Control System (VCS) allow us to add lots of information and meta-data to our source code

## Now What?
- Demo a git repository's history (repo is a folder)
- Pick up our fundamental git vocabulary
    - repo is short for repository
    - repository is a git enable folder
    - local means your computer your working on
    - remote means a remote computer where you're backing stuff up
    - diff means to show differences - what's new? what's removed?
    - "commit" means one or more changes to one or more files
    - commits are our save points.
    - commit messages are meta-data that explain each commit
- Two ways to work with git:
    - We'll make repos on GitHub and clone them to our laptop
    - We'll make repos on our laptop then add github as a remote and push to github
- Let's git after it!



## Our First Time Workflow to Setup a Repo (one time setup)
- Choose if we're going to start on GitHub or our laptop (remote or local)
- Recommend we start remote with the following directions:
    - Go to https://github.com/new
    - Name your repo and give it a description
    - Skip all the boxes and click the green "create repo" button
    - copy the SSH address of our new empty repo
    - Clone our repository down to our local computer, making a new folder
    - to clone, we type "git clone " then paste that clone address
    - this makes a copy of the repo locally

## Our Daily Workflow



## Useful commands
- `git status`
- `git remote -v` shows all of your remotes


## Lay of the Land
~/Desktop/codeup-data-science is a regular folder
~/Desktop/codeup-data-science/database-exercise will be a git repo
~/Desktop/codeup-data-science/classification-project will be a git repo
