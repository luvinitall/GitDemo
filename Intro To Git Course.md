# Intro To Git Course
---
## Agenda / Goals
- We will answer some questions about what Git is and why a source control system is so important for a development team.
- We will go over some very basic Git commands and explore how to use different tools to invoke Git actions: Terminal, Source Control in VS Code, GitHub/GitHub Desktop
- We will introduce the concept of Git Branches
- At the end of the course, you should feel comfortable with cloning a repository and getting starting with collaborative development using Git and GitHub
- New Bullet Point

## New Section

## Part 1 - What is Git
- At it's heart, Git is a program that runs on your Mac and is used to create repositories to record various snapshots of what happens within a repository.  It integrates with the Mac Terminal, and can be invoked using a set of various commands.  Opening up a terminal and type `git help` to see many of the commands you can execute.
- Git is the most popular world wide tool used in the development community to-date.  There are other popular source control systems, and each work a bit differently, but Git is the hands down leader and has the most support accross different tooling and Operating Systems.
- The Git Repository stores information about changes performed on tracked files and folders within that top level folder
- In addition to integrating with the terminal, most IDEs support integration with Source Control and Git.
- Finally, there are a bunch of online sites used for collaboration like the one we use at GR, GitHub, which are designed around hosting Git repositories online.
- *DEMO* 
    - Create a new repo (first make sure Email/Name are configured)  `git init` and  `git status`, or use the IDE
    - Working folder, staging, committed
    - Add some files, `git add` or `git rm`, or use the IDE
    - Talk about tracked/untracked vs staged vs committed.
    - Look at how to rewrite local history by removing the last commit when a mistake is made.
## Part 2 - Branching
- In addition to GitHub's ability to easily track changes to files and folders, at it's core, GitHub supports the ability to create code branches and supports working with branches in a way that encourages develpers to take advantage of this important paradigm.
- *DEMO* 
    - Create a new branch
    - Commit a change and then push the changes up.
    - Talk about fetching, pulling, pushing
- Branches allow people to collaborate on work in progress without impeding work by others working on the main/master branch.  This allows for several features to be developed in parallel and only merged as they are ready.


## Let's talk about Stashing
- Stashing allows you to take some changes and put them away for possible use for a later point