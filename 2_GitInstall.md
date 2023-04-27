# Getting Started

## Do you have Git installed?
Since we will be working with Mac's, all the steps are for MacOs. Most MacOs computers have Git pre-installed you just have to get it activated. If you want to work from home you have to take a couple of more steps. 

Open Terminal by opening [Spotlight](https://support.apple.com/guide/mac-help/search-with-spotlight-mchlp1008/mac) pressing Command button + Spacebar on keyboard.

For windows keyboards the **Windows** key is the Command button.  When you do this the Spotlight will appear:

<img src="images/spotlight.png" width="50%" height="50%">

Enter Terminal in the spotlight search and select Terminal from the apps. Terminal window will open up:

<img src="images/terminalwindow.png" width="40%" height="40%">

Many of the Git commands are run in Terminal. What is Terminal? The Mac Terminal is a command line interface (CLI) for the macOS operating system (OS). There is an excellent 15min video for [Beginners](https://www.youtube.com/watch?v=aKRYQsKR46I). Please take a moment to view the video. If interested in learning more on your own time, a more in depth explanation can be found [here](https://www.youtube.com/watch?v=ogWoUU2DXBU). 


Make sure to confirm that you have Git installed. You can do this by running the following command in Terminal:
```
$ git --version
```
Terminal will show something like this:
```
git version 2.39.2
```

Not insatlled? Here is a guide on how to install Git on your computer: [Install Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git). Follow steps in order to install Git (make sure to follow steps for your operating system - MacOs or Windows ). 

Once you get git installed we need to customize the environment. Before we do that, do you have a GitHub account? If you do great, if not please create one here [GitHub Sign Up](https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home). Make sure to use your **personal** email when creating the GitHub account. You will need to create a GitHub account in order to remotely access the repository. Remember Git is local, GitHub is remote.  

Once you have confirmed that Git is installed you want to customize the environment. 

Open terminal on your Mac. From the terminal command prompt lets make sure to set up your identity by setting your user name and email address. This is important because every Git commit uses this information, and it’s immutably baked into the commits you start creating. In terminal enter the following (enter **your** information inside the quotation marks): 
```
$ git config --global user.name "your-github-user-name"
$ git config --global user.email "your@email.com"

