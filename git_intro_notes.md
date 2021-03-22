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
- Another way to setup your repos is to start locally on your computer. [Directions are here](https://ds.codeup.com/fundamentals/git/)

## Our Daily Workflow
- do work until you've finished a thing or fixed a thing...
- do work, add lines to files, make new files, edit files, delete, whatever...
- `git status` to show which files changed
- `gid diff` to see what has changed in those files
- `git add filename` (where filename is an actual filename)
- run `git status` again to see that file show green
- Adding a file is like putting a letter in an envelope..
- `git commit` will open your editor so you can type the commit message
- save and close that editor window
- we can add one or more changes to each commit
- `git push` uploads any commits we have to your remotes
- lather, rinse, repeat...

## Useful commands
- `git status`
- `git remote -v` shows all of your remotes
- `git diff` before any adding/commiting shows changes

## Lay of the Land
`~/Desktop/codeup-data-science` is a regular folder
`~/Desktop/codeup-data-science/database-exercise` will be a git repo
`~/Desktop/codeup-data-science/classification-project` will be a git repo


## Useful Notes
- think of a "commit" as a fancy signed, sealed, wax stamped fancy envelope from from some fancy desk
- a push could contain 1 or 2 or n amount of commits, where n is a positive number
- commit early, commit often
- commits should be a complete thought or fix or feature
- push your commits at least once or twice a day
- "If it ain't in version control, then it doesn't exist"
- "Git Push every day"

- Making a directory is making a directory
- mkdir some_directory
- Repos are special folders (where a git init has been done)
Creating a repository:
- we can create on github and clone down. (in this case, GitHub is doing the mkdir then doing the git init inside of that folder on their servers). When we clone this, we're getting copy of this new folder that was initialized as a git repo
- alternative method is to create the folder on your laptop first then running git init.
~/Desktop/codeup_data_science/
~/Desktop/codeup_data_science/database-exercises/
~/Desktop/codeup_data_science/python-exercises/
~/Desktop/codeup_data_science/regression-exercises/
~/Desktop/codeup_data_science/regression-project/
Avoid repos inside of repos.
- If your commit message is kinda short, you can do `git commit -m "this is my commit"`
