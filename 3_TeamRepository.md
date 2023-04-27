# Working in a Team:  

One of the many benefits of Git is that it allows many developers to work on the same code at once. Once they have made changes and checked to see if their code works they can submit a pull-request to have it merged to the central repository.  

## What is a pull-request:
A pull request is an event to notify software developers that an engineer has pushed code to a specific Git branch (or a specific version of the code repository) for a colleague to review. Once a developer opens a pull request, your team can review the potential changes introduced before merging with the central repository branch. 

## What’s the difference between a Pull and a Push?
The difference between a “pull” and a “push” is as intuitive as you think. A developer will pull to request a target repository to pick up their local changes and merge them into the existing code. A push is not a request, but a **command** (git push) used to “upload” local content or changes to a remote repository. Many of you have been pushing your code to your own repository. 

## The Anatomy of a Good Pull Request 
Whenever a developer opens a pull request, they should be sure to include all of the following components: 

### The Title
The title should be a meaningful summary of the purpose of the PR. Often this can correspond to a ticket, service, or component. 

### The Description
The description should include changes the developer introduced so the reviewer knows what to look out for. 

### Commits
Each relevant commit should be included in your PR and each commit should have a concise description of code changes. 




This repository will be a simple web page that everyone contributes to. Contribution will be limited to adding info to the website. Please note that letters in <italics> are examples and % is the Terminal prompt.  

 

1. In Terminal navigate to your work folder and create a new folder for the exercise:   
```
%mkdir c14Website 
```

2.  Change to the folder:  
```
%cd c14Website  
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

 

 
