# 3. Collaboration and Sharing

| *What you will Learn* |
|---|
|<ul><li> How to grant access to a repository</li><li> How to clone a repository</li></ul>|

A positive aspect of sites like Github and Bitbucket is to allow for collaboration on projects. In this lesson, we will show you how to give other people access to your repository, and then how to clone a repository remotely on your device.

### What is Cloning?
Cloning a repository creates a remote access point to viewing and alter the source code in your repository. A copy of the source code is downloaded (cloned) to your device that you can work on. Then, when you have completed a feature, you can push your changes back to the repository (but more on that later). Cloning allows you to work on a feature without impacting your repository - because the changes you make to the source code are only applied to your local device and only updates the repository when you tell it to (pushing). 

## 3.1 Grant Access
If you are the group member who hosts the repository you will need to:

1. Navigate to your repository page and select the "Invite" button in the top right of the page
2. Enter all your group members email addresses. Make sure you give them "write" privledges

If you are **not** the group member who hosts the repository you will need to:

1. Once the host of the repository has finished their instructions, check your email for an invitation to have "write" access to the repository and accept that invitation.

Before moving on to the next step, make sure that everyone in your group has accepted their invitation, otherwise they will not be able to make changes to the repository.

## 3.2 Clone the Repository
Now that everyone has access to the repository, you should clone a remote copy onto your device so that you can make changes. In order to do this, you need to have a terminal window open and a copy of the repository code that looks something like:

`https://YOUR_USERNAME@bitbucket.org/HOST_USERNAME/PROJECT_NAME.git`  

You should find this on the repository main page when you select the button "clone".

1. Navigate to the directory you want to save your clone of the source code in. (e.g. if you had a folder called "projects" you could save it in `/home/pi/projects`
2. Type the following command into your terminal in order to clone the source code from your repository link:  
`git clone YOUR_URL_HERE`
3. `cd` into the cloned folder and you should be able to view all of the source code from the repository.


Well done! You now have a copy of the source code on your own device for you to work on, and any changes you make will only impact your local device.


***[Next -> 4. Committing and Pushing]()***

