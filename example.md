The __Hello World__ project is a time-honored tradition in computer programming.
It is a simple exercise that gets you started when learning something new. 
Let’s get started with GitHub!

### You’ll learn how to:

* Create and use a repository
* Start and manage a new branch
* Make changes to a file and push them to GitHub as commits
* Open and merge a pull request

# What is GitHub?
GitHub is a code hosting platform for version control and collaboration. 
It lets you and others work together on projects from anywhere.

This tutorial teaches you GitHub essentials like repositories, branches, commits,
and Pull Requests. You’ll create your own Hello World repository and learn 
GitHub’s _Pull Request_ workflow, a popular way to create and review code.

### No coding necessary
To complete this tutorial, you need a GitHub.com account and Internet access.
You don’t need to know how to code, use the command line, or install Git 
(the version control software GitHub is built on).

Tip: Open this guide in a separate browser window (or tab) so you can see it
while you complete the steps in the tutorial.


# Step 1. Create a Repository
A __repository__ is usually used to organize a single project. Repositories can contain folders and files, images, videos, spreadsheets, and data sets – anything your project needs. We recommend including a _README_, or a file with information about your project. GitHub makes it easy to add one at the same time you create your new repository. _It also offers other common options such as a license file._

Your ```hello-world``` repository can be a place where you store ideas, resources, or even share and discuss things with others.

## To create a new repository
In the upper right corner, next to your avatar or identicon, click  and then select _New repository._
Name your repository ```hello-world```.
Write a short description.
Select __Initialize this repository with a README.__

Click __Create repository.__

# Step 2. Create a Branch
__Branching__ is the way to work on different versions of a repository at one time.

By default your repository has one branch named ```main``` which is considered to
be the definitive branch. We use branches to experiment and make edits before
committing them to ```main```.

When you create a branch off the ```main``` branch, you’re making a copy, or snapshot, 
of ```main``` as it was at that point in time. 
If someone else made changes to the ```main``` branch while you were working on your branch, 
you could pull in those updates.

This diagram shows:

* The ```main``` branch
* A new branch called ```feature``` (because we’re doing ‘feature work’ on this branch)
* The journey that ```feature``` takes before it’s merged into ```main```


Have you ever saved different versions of a file? Something like:

* ```story txt```
* ```story-joe-edit.txt```
* ```story-joe-edit-reviewed.txt```

Branches accomplish similar goals in GitHub repositories.

Here at GitHub, our developers, writers, and designers use branches for keeping
bug fixes and feature work separate from our main (production) branch.
When a change is ready, they merge their branch into ```main```.

### To create a new branch
Go to your new repository ```hello-world```.
Click the drop down at the top of the file list that says __branch: main.__
Type a branch name, ```readme-edits```, into the new branch text box.
Select the blue __Create branch__ box or hit “Enter” on your keyboard.
branch gif
