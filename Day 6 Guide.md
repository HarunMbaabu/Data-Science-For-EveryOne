## **Git for Data Science: What every data scientist should know about Git.** 

### **Introduction to Git**
A version control system called Git is made to keep track of changes made to a source code over time.

Without a version control system, a collaboration between multiple people working on the same project is complete confusion. As no one has kept track of their modifications and it becomes very difficult to combine them into a single fundamental fact, resolving the eventual conflicts becomes impossible. Git and more advanced systems built on top of it (such as GitHub) provide tools to solve this issue.

Typically, each user will clone a single central repository to their local system (referred to as "origin" or "remote") which the individual users will clone to their local machine (called "local" or "clone"). Users "push" and "merge" their completed work back into the central repository once they have stored relevant work (referred to as "commits") on their computers.

### **Difference between Git and GitHub**
Git serves as both the foundational technology, for tracking and merging changes in a source code, and its command-line client (CLI).

An online platform called GitHub was created on top of git technology to make it simpler. Additionally, it provides capabilities like automation, pulls requests, and user management. GitLab and Sourcetree are two additional options.

### **Git for Data Science**
In data science we are going to analyze the data using some models and algorithms, a model might be created by more than one person which makes it hard to handle and makes updates at the same time, but Git makes this all easy by storing the previous versions and allowing many peoples to work on the same project at a single time.

### **Terminology.** 
- Repository - "Database" of all the branches and commits of a single project

- Branch - Alternative state or line of development for a repository.

- Merge - Merging two (or more) branches into a single branch, single truth.

- Clone - Creating a local copy of the remote repository.

- Origin - Common alias for the remote repository which the local clone was created from

- Main / Master - Common name for the root branch, which is the central source of truth.

- Stage - Choosing which files will be part of the new commit

- Commit - A saved snapshot of staged changes made to the file(s) in the repository.

- HEAD - Shorthand for the current commit your local repository is currently on.

- Push - Pushing means sending your changes to the remote repository for everyone to see

- Pull - Pulling means getting everybody else's changes to your local repository

- Pull Request - Mechanism to review & approve your changes before merging to main/master

### **Basic commands**
- git init - Create a new repository on your local computer. 

- git clone - Start working on an existing remote repository.

- git add - Choose file(s) to be saved (staging).

- git status - Show which files you have changed.

- git commit - Save a snapshot (commit) of the chosen file(s).

- git push - Send your saved snapshots (commits) into the remote repository.

- git pull - Pull recent commits made by others into your local computer.

- git branch - Create or delete branches.

- git checkout - Switch branches or undo changes made to local file(s).

- git merge - Merge branches to form a single truth.

Reference: 

- Git Tutorial for Beginners: Learn Git in 1 Hour: https://youtu.be/8JJ101D3knE?si=ue4-uYxAPf7s_pEX


- Standout as a Data Analyst with THIS TOOL : https://youtu.be/aw14VK9sN2s?si=FdR87hOoa4DltA91




