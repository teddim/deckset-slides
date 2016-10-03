build-lists: true


# Git

---

# Objectives
- Discuss what a Version Control System is
- Describe how Git works
- Initialize a git repository with git init
- Check the status of changed files in a git repository with git status
- Stage and Commit files


---

# Version Control System

Version control allows developers to revert back to a specific time and place in your code... sort of like a reset button.

![right filtered](file:///Users/teddimaull/Desktop/pixabayimages/backwards-1426683_1920.png)

^ Keep track of changes to files over time
^ View or return to a previous state of your project
^ Manage changes to files from multiple people
^ Make changes without worrying about stability
^ Easy to share with others
^ "Save points" in the code

^ Have you ever worked on a file and wished you could go back to how it looked an hour ago?
^ First objective

---

# Git is the Solution
Git is a Version Control System. Any files tracked by git typically go through 3 stages:

Unstaged

^ These changes will not be committed in the next commit

Staged

^ These changes will be committed in the next commit

Committed

^ Changes committed in the last commit
^ Second objective

---

# `git init`

^ initialize a git repository to start tracking your changes
^ Third Objective

---

# `git status`

^ see the status of your changed files (are they in the staging area or committed yet? Are some files not being tracked?)
^ Fourth Objective

---

# `git add`
![right](file:///Users/teddimaull/Desktop/pixabayimages/discovery-space-shuttle-879406_1280.jpg)

^ We are adding the changed files to the staging area
Almost done with 5th objective

---

# `git commit`
![right](file:///Users/teddimaull/Desktop/pixabayimages/discovery-space-shuttle-879410_1280.jpg)

^ you will need to add a commit message
^ good practice is to add a detailed message in the present tense
^ commit early, commit often
^ done with Fifth objective

---
# Let's Put it All Together
- `git init`
- `git status`
- `git add -a`
- `git commit -m "complete the lesson"`

^ Explain what is happening at each step
Remind that init only happens ONCE per repository and only when creating a new repo

---

# White Board Time
![](file:///Users/teddimaull/Desktop/pixabayimages/colors-1267036_1920.jpg)

^ Checks for Understanding:
 I want to initialize a repository
 I want to check the status of my repository
 I have created a new file and I want to add it to the staging area
 I have some files staged and want to commit them to my local repository

---
# BREAK

![](file:///Users/teddimaull/Desktop/pixabayimages/emblem-1294453_1280.png)

---
# GitHub

---

# Objectives
- Discuss the difference between Git and GitHub
- Connect Git and GitHub
- Send files from Git to GitHub

---

# What is GitHub?
GitHub acts as a remote backup service for git repositories.

![](file:///Users/teddimaull/Desktop/pixabayimages/mars-1326108_1280.jpg)

^ Git and GitHub are not the same thing. Git is version control software and GitHub is a place to backup or store the same files that are being tracked by Git.

---

# Connect Git and GitHub
`git remote add origin git@github.com:nasa/marooned-astronaut.git`

![](file:///Users/teddimaull/Desktop/pixabayimages/entrepreneur-1103717_1280.jpg)

^ link to the github repository by referencing the account and the name of the repository from github. You need to set up the flight path.

---
# Send the files to GitHub

`git push origin master`

![right](file:///Users/teddimaull/Desktop/pixabayimages/rocket-launch-67649_1920.jpg)

---

# What's Next? Practice!
http://learngitbranching.js.org/
Main - Introduction Sequence 1 - 3
Remote - Push & Pull Sequence 1 - 4

---

# Git/GitHub Q&A
