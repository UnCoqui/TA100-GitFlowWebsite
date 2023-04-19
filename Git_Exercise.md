# GIT Project Workflow Exercise 
#What is Git?
Git is the most commonly used version control system. Git tracks the changes you make to files, so you have a record of what has been done, and you can revert to specific versions should you ever need to. Git also makes collaboration easier, allowing changes by multiple people to all be merged into one source. 

So regardless of whether you write code that only you will see, or work as part of a team, Git will be useful for you.

Git is software that runs locally. Your files and their history are stored on your computer. You can also use online hosts (such as GitHub or Bitbucket) to store a copy of the files and their revision history. Having a centrally located place where you can upload your changes and download changes from others, enable you to collaborate more easily with other developers. Git can automatically merge the changes, so two people can even work on different parts of the same file and later merge those changes without losing each other’s work!
 

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

 

 
