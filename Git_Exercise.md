# Introduction
## What is Git and GitHub?
### Git: 
Version control, also known as source control, is the practice of tracking and managing changes to software code ovr time.  [**Git**](https://git-scm.com/about) a distributed version control software and is the most commonly used version control system. Being distributed means that every developer working with a Git repository has a copy of that entire repository - every commit, every branch, every file. Git tracks the changes you make to files, so you have a record of what has been done, and you can revert to specific versions should you ever need to. Git also makes collaboration easier, allowing changes by multiple people to all be merged into one source.  

So regardless of whether you write code that only you will see, or work as part of a team, Git will be useful for you. In some cases it may even be a required skill for employment.

Git is software that runs locally. You normally use Terminal (MacOs) or Git Bash (Windows) and use commands to manage the repository. Your files and their history are stored on your computer.  Git can automatically merge the changes, so two people can even work on different parts of the same file and later merge those changes without losing each other’s work!

What does the work flow look like? The green is the master or main source code. Each circle represents a commit or chnage in teh software. The green and orange are branches of the main  

![Git work flow](/images/git-branches-merge.png)

 
### GitHub:
GitHub is a for-profit company that offers a cloud-based Git repository hosting service. Essentially, it makes it a lot easier for individuals and teams to use Git for version control and collaboration. So while Git is storing your code locally, GitHub is where you can store your code remotely and share with others. It's important to remember that GitHub is **_not_** Git. There are other companies who offer hosting services that do the same thing as GitHub, such as Bitbucket and GitLab.

GitHub’s interface is user-friendly enough so even novice coders can take advantage of Git. Without GitHub, using Git generally requires a bit more technical savvy and use of the command line.



What does the work flow look like? The green is the master or main source code. The green and 


## Set up a practice repository in NFAR:  


This repository will be a simple web page that everyone contributes to. Contribution will be limited to adding info to the website. Please note that letters in <italics> are examples and % is the Terminal prompt.  

 

1. In Terminal Create a folder for the exercise:   
```
%mkdir <folder_name> 
```

2.  Change to the folder:  
```
%cd <folder_name>  
```
3. Clone the directory. You can get the clone address by navigation to the repository and click on <>Code and copy the HTTPS URL address 

```
%git clone https://github.com/<YOUR-REPOSITORY> 	 
```
4.  Create a branch for your changes: 
```
%git branch <branch-name> 
```
5. Switch to the new branch: 
```
%git checkout <branch-name> 
```
6. Now you can push this branch up to git hub:  
```
%git push –u origin <branch name> 
```

7. Check that the branch has been successfully pushed up. To confirm that the branch has been pushed, head over to GitHub and click the branches drop-down. You should see the branch there: 

![branch-dropdown](images/gitBranchDropDown.jpg)

Now that you have a local branch and have it showing up remotely you can make changes to the local repository.  

STOP! Always check to see what branch you’re on. To check to see what branch you are on enter the following command in Terminal:  

%git status 

 

Git Status in Depth: Understanding Your File States | CloudBees 

This will let you know what branch you are currently on other pertinent information about files.   

Make changes to the home.html page. Make the following changes: 

Add your First and Last Name 

A sentence that mentions some of your hobbies (i.e. “My hobbies are reading, playing D&D, and hiking”) 

Your autest email address.  

DO NOT CHANGE IMAGE 

Once you are satisfied with your changes proceed to add the file and commit your changes: 

%git add home.html 

%git commit –m “Your comments here” 

%git push 

 

 
