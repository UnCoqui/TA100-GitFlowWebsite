# Introduction
## What is Git and GitHub?
### Git: 
Version control, also known as source control, is the practice of tracking and managing changes to software code over time.  [**Git**](https://git-scm.com/about) is a distributed version control software and is the most commonly used version control system. A Git repository tracks and saves the history of all changes made to the files in a Git project. It saves this data in a directory called .git, also known as the repository folder. Git tracks the changes you make to files, so you have a record of what has been done, and you can revert to specific versions should you ever need to. Being distributed means that every developer working with a Git repository has a copy of that entire repository - every commit, every branch, every file. Git also makes collaboration easier, allowing changes by multiple people to all be merged into one source.  

So, regardless of whether you write code that only you will see, or work on as part of a team, Git will be useful for you. In some cases it may even be a required skill for employment.

Git is software that runs **locally**. You normally use Terminal (MacOs) or Git Bash (Windows) and use commands to manage the repository. Your files and their history are stored on your computer.  Git can automatically merge the changes, so two people can even work on different parts of the same file and later merge those changes without losing each other’s work! 

But wait, if Git is run locally how can everyone be making changes? That is were GitHub comes in.


### GitHub:
GitHub is a for-profit company that offers a cloud-based Git repository hosting service. Essentially, it makes it a lot easier for individuals and teams to use Git for version control and collaboration. So, while Git is storing your code locally, GitHub is where you can store your code remotely and share with others. It's important to remember that GitHub is **_not_** Git. There are other companies who offer hosting services that do the same thing as GitHub, such as Bitbucket and GitLab, but GitHub is by far the most widely used, with over 100 million developers.

GitHub’s interface is user-friendly enough so even novice coders can take advantage of Git. Without GitHub, using Git generally requires a bit more technical savvy and use of the command line.

### GitHub Workflow:
What does the work flow look like? Each circle represents a commit or change in the software. The green is the master or main source code. The blue and orange are branches of the main branch. Notice that you can have other branches of the code that can eventually merge into the main branch.  

<img src="/images/git-branches-merge.png" width="50%" height="50%">


## [Next - Step 2: Installing Git](2_GetStarted.md)
