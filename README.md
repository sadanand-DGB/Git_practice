# Git_practice
Git concepts
This repository is created for practicing and understanding the fundamentals of Git and GitHub.

Topics Covered

• Git fundamentals
• Git workflow
• Working Directory
• Staging Area
• Local Repository
• Remote Repository
• Basic Git commands
• Git branches
• Branch switching
• Branch merging
• .gitignore

Git Workflow

Working Directory → Staging Area → Local Repository → Remote Repository

Basic Commands

git init
git status
git add .
git commit -m "message"
git log
git branch
git switch
git merge

Branching

Branches are used to work on different features independently.

git branch feature-name
git switch feature-name

Or create and switch to a branch directly:

git switch -c feature-name

Merging

To merge a feature branch into the main branch:

git switch main
git merge feature-name

Git Ignore

The .gitignore file is used to prevent unwanted files and directories from being tracked by Git.

Examples:

secret.txt


Purpose

The purpose of this repository is to practice Git commands, understand the Git workflow, and learn how to manage changes using branches and commits.
