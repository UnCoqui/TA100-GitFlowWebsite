# Team Website Contribution
Now you get to make some changes. The website has "cards" to display some information for each cohort. Each person will be assigned a cohort number and will only make changes to that "card". 

### 1. Navigate to your folder:
Open Terminal and navigate to your project folder. Make sure to checkout the branch you created earlier and check status - this is important. 

### 2. Open VSCode

### 3. Make the assigned changes to the website
Each person will be assigned a cohort card number. You can find in in the the HTML under "title" ```<p class="title">COHORT 1</p>```. 
```
 <div class="column">
          <div class="card">
            <img src="images/SamplePic.jpg" alt="Cohort1">
            <div class="container">
              <h2>Your Name</h2>
              <p class="title">COHORT 1</p>
              <p>Some text that describes me lorem ipsum ipsum lorem.</p>
              <p>example@example.com</p>
              <p><button class="button">Contact</button></p>
            </div>
          </div>
        </div>
        
 ```       
You will update the following: 
- Upload your picture to the image folder (shoulder and up). We can take picture here. 
- Change the `img src=` to point to the image you uploaded
- In the `<h2>Your Name` enter your First and Last Name
- In the `<p>Some text...` enter short sentence that describes somethign about you (i.e. maybe a hobby, that you are a Tech Participant at NFAR, etc.)
- in the `<p> example@example.com` enteryour@autest.net email address
### 5. Preview your work
In order to preview your work you can view in your browswer using liveserver  

<img src="images/SelectLiveServer.jpg" width="40%" length="40%"> 

### 4. Commit changes to your branch

```
%git add home.html

%git commit –m “changes to card "#" ”

%git push
```
