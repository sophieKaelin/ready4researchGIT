<!--What about a definitions page? IDE, GUI, Git, Github, Bitbucket-->

# Day 2 - Version Control with Git

![Git Linked List Example](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT-gtjD0wp0QJuTGvA0pjHgFYgWPmzb92tu-w&usqp=CAU)

## Intro

<!-- Some intro into why git is important and useful -->
In this workshop we will be focussing on learning more about Git, which is a version control system used to track changes to files during a project. Version control is important in larger projects which multiple developers are working on, because changes by one person may impact changes made by another person, and there needs to be a constient and simple way to resolve those conflicts. Git also alows you to look through the history of your work so you can undo any changes that may have brocken your program. <!--Its sort of like using a live Google Doc for a group project so lots of users can collaborate (sort of ... not really).--> You will use Git in this project to track the changes you make to the mini console.

### Git vs Github/Bitbucket
You may have heard of names like [Github](https://github.com/) and [Bitbucket](https://bitbucket.org/). These are platforms that host/store your source code for a project and uses Git to enable version control. So Git, Github and Bitbucket are not names to be used synonamously. If you want to read more about the differences, have a read through [this](https://www.theserverside.com/video/Git-vs-GitHub-What-is-the-difference-between-them) article. 

For this project, the software is hosted on **Bitbucket**

### But what about Git GUI's?

There are many ways of interacting with Git. The most basic is through the command line, typing commands directly into the shell. However, there have been some Graphical User Inteferfaces (GUI's) developed to make using Git in your project simpiler. A lot of Integrated Development Environment's (IDE's) like Visual Studio and Eclipse have functionality to import projects from Git or Bitbucket and interact with Git through their platform. You can also interact from the Github and Bitbucket webpages. 

For this project, you will be interacting with Git through the command line you experimented with yesterday. Those of you who have used Git before may be wondering why we aren't using the bitbucket website, or other GUI's to interact with Git. While these are fine (and handy) ways of using Git, it is important how to learn the basics through command line to develop a good understanding of what goes on in the background when you use these interfaces.

To read more on the pros and cons of Git GUI's and command line, have a read of [this](https://practicalgit.com/blog/learn-git-gui-or-command-line.html#:~:text=Git%20CLI%3A%20CLI%20stands%20for,tell%20Git%20what%20to%20do.&text=Git%20GUI%3A%20GUI%20stands%20for,offer%20an%20interactive%20Git%20experience.)

### Git command structure

<!--TODO: Structure of Git commands something like Git verb blah-->
<!--Point of reference for common git commands (push, pull etc.)-->
<!--TODO: Add ensure you have set everything up from yesterday.-->

## Lessons

[1. Getting Code with Git]()
   
  * [Forking (Creating a Copy of the Project)](#forking)
  * [Collaboration and Sharing](#collaboration-and-sharing)<!--types of repos (private, public, starred. Intro multiple user access. intro to conflicts later)-->

[2. Changing Code in Git]()  

  * [Commiting](#commiting)
  * [Pushing](#pushing)
  * [Pulling](#pushing)
  * [Conflicts](#conflicts)<!--TODO: Force a conflict-->

[3. Getting your Work Incorporated]()

  * [Pull Requests](#pull-requests)
  * [Ignoring Things](#ignoring-things)
  * [Summary](#summary) <!--Which elements will be the most important for remainder of this project-->

