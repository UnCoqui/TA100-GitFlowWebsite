# Team Web Site!!
For our team project we will work on a website that will NOT be publicly available. It will only run locally on your invidual machines.  

This repository will be a simple web page that everyone contributes to. Contribution will be limited to adding personal info to the website. Please note that letters in <italics> are examples and % is the Terminal prompt.  

 

### 1. In Terminal navigate to your work folder and create a new folder for the exercise:   
```
%mkdir c14Website 
```

### 2. In Terminal Change to the folder:  
```
%cd c14Website  
```
### 3. Clone the directory. You can get the clone address by navigation to the repository and click on green <>Code and copy the HTTPS URL address 
 <img src="images/gitCloneCode.jpg" width="40%" length="40%"> 
 In Terminal clone the repository: 
 
```
%git clone https://github.com/TechCohort14/TA100-GitFlowWebsite.git 	 
```

### 4.  Create a branch for your changes:  
Make sure to follow the this naming convention: _<yourfirstnameFeature>_ <br>
First name is lowercase, the first letter of the "Feature" is uppercase. Team member Ryan is working on updating the picture then the branch name would be: <br>
 _ryanPicture_ 
 
```
%git branch <yourfirstnameFeature> 
```
### 5. Checkout the new branch: 
You created a branch, but you must change to it. If you don't change to the branch you will be making changes to the main branch and your changes will NOT be accepted. <br>
STOP! Always check to see what branch you’re on. To check to see what branch you are on enter the following command in Terminal:  
```
%git status 
```
<img src="images/gitStatus.jpg" width="40%" length="40%">  
 
```
%git checkout <yourfirstnameFeature> 
```
### 6. Now you can push this branch up to git hub:  
```
%git push –u origin <branch name> 
```
### 7. Check that the branch has been successfully pushed up. To confirm that the branch has been pushed, head over to GitHub and click the branches drop-down. You should see the branch there: 

![branch-dropdown](images/gitBranchDropDown.jpg)

Now that you have a local branch and have it showing up remotely you can make changes to the local repository.  

### 8. Make the assigned changes to the website
Each person will be assigned the scetion of code they will change
 
### 9. Commit changes to your branch




Once you are satisfied with your changes proceed to add the file and commit your changes: 

%git add home.html 

%git commit –m “Your comments here” 

%git push 

 

 

