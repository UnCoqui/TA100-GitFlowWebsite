# Team Web Site!!
For our team project we will work on a website that will NOT be publicly available. It will only run locally on your invidual machines.  

This repository will be a simple web page that everyone contributes to. Contribution will be limited to adding personal info to the website. Please note that letters in <italics> are examples and % is the Terminal prompt.  

 

### 1. In Terminal navigate to your work folder and create a new folder for the exercise:   
```
%mkdir c14Website 
```

### 2.  Change to the folder:  
```
%cd c14Website  
```
### 3. Clone the directory. You can get the clone address by navigation to the repository and click on <>Code and copy the HTTPS URL address 

```
%git clone https://github.com/TechCohort14/TA100-GitFlowWebsite.git 	 
```
### 4.  Create a branch for your changes:  
Make sure to follow the this naming convention:<yourfirstname_feature> <br>
Here is an example. If you are working on updating the picture, then use your first name and then Picture <br>
 _ryan_picture_ 
 
```
%git branch <yourfirstname_feature> 
```
### 5. Switch to the new branch: 
```
%git checkout _<branch-name>_ 
```
### 6. Make the assigned changes to the website
You will be given instructions on what changes to make to the code. 
 
### 7. Commit changes to your branch
 
### 6. Now you can push this branch up to git hub:  
```
%git push –u origin <branch name> 
```

### 7. Check that the branch has been successfully pushed up. To confirm that the branch has been pushed, head over to GitHub and click the branches drop-down. You should see the branch there: 

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

 

 

