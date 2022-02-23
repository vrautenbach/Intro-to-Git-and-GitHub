# Introduction to Git and GitHub

## Recap
[Git](https://git-scm.com/) is a version control system used to organize code, keep track of changes made and collaborate with people.

[GitHub](https://github.com/) is a web-based hosting service for version control using Git, commonly used for sharing the code with the world.

If you don't understand the basic concepts yet, I would highly recommend that you have a look at the [Git and GitHub for Beginners - Crash Course](https://www.youtube.com/watch?v=RGOj5yH7evk). It is about an hour, but will cover all of this in detail.

Other great resources to consider:
* [Git and GitHub Tutorial – Version Control for Beginners](https://www.freecodecamp.org/news/git-and-github-for-beginners/)
* [Getting started with Git](https://docs.github.com/en/get-started/getting-started-with-git/setting-your-username-in-git) and [Using Git](https://docs.github.com/en/get-started/using-git/about-git)
* [W3C Git Tutorial](https://www.w3schools.com/git/git_tutorial.asp)
* [GitKraken Git Tutorial](https://www.gitkraken.com/learn/git/tutorials)
* [GitHub YouTube playlist with training resources](https://www.youtube.com/playlist?list=PLIRjfNq867be7VngMuXsjTvzBM26nBINg)
* [GitHub learning platform](https://lab.github.com)
<br><br>

## Task 1: Local repository

Before starting the task, take a couple of minutes and review the basic terminal commands, https://github.com/vrautenbach/geoinformatics-notes/blob/master/terminal-commands.md You will use these throughout the session, and it would be good, if you understand them. 

The command line in Windows can be a bit difficult to use, so I would recommend that you use the [VS Code](https://code.visualstudio.com) terminal. During this semester we will be using VS Code as our main editor and some other editors for collaborative work. 

For task 1, you will open up your command line (preferably VS Code) and complete the following:
- [ ] Create a directory using the command ```mkdir```
- [ ] In the directory you created initialize Git using ```git init```
- [ ] Create a README.md file in your directory using the ```echo $null >> filename``` command
- [ ] Make sure README.md is in your Working Directory by checking your status with ```git status```
- [ ] Open your README.md file in VS Code and add your name as a level 2 heading (remember to save your file)
- [ ] Move README.md from the Working Directory to the Staging Area by using ```git add```
- [ ] Make sure README.md is in your Staging Area by checking your status with ```git status```
- [ ] Commit README.md to your repository using ```git commit```
- [ ] Make sure your Working Directory and Staging Area are clean with ```git status```
- [ ] Make sure your commit has been logged into your repository by using ```git log```

Take a screenshot of your terminal, with the steps above, and upload your screenshot to a new Issue titled *Task 1*. In the body of the issue, you can drag and drop your screenshot or search for it on your device. Once you have added the screenshot you can submit the issue and move to the next task.

_If you are unsure of the process for creating a new issue, have a look at https://docs.github.com/en/github/managing-your-work-on-github/creating-an-issue_
<br><br>

## Task 2: Remote repository on GitHub

For task 2, you will have to do the following:
- [ ] In GitHub, in this repository, you need to find the repository URL in the root of the repository. You should see a button that says ```Clone or Download```, copy the URL and head over to the command line.
- [ ] In your terminal (on your computer in VS Code in a new session) you want to type ```git clone <YOUR URL>``` where you add the URL in the place of ```<YOUR URL>```. You will notice that there is some network activity happening.
- [ ] Once the network activity finishes, type ```ls``` and you will notice you have the repository on your local machine. You can ```cd``` into the repository and see all the files that are on GitHub are now on your local machine.

Take a screenshot of your command line showing how you cloned this repository onto your local machine. Create an Issue with the title *Task 2* and include the screenshot in the body of the issue.
<br><br>

## Task 3: Branching

For task 3, you will have to do the following:
- [ ] Create a new branch called ```assignment-edit``` on the terminal of your local repository on your computer.
- [ ] Create a new file called ```new-branch.md``` in the ```assignment-edit``` branch, and add your name at the top of the document. Style it using [Markdown](https://www.markdownguide.org/basic-syntax/).
- [ ] Once you have edited ```assignment-edit```, push those changes to GitHub.
- [ ] On GitHub create a Pull Request to merge these changes into the Master branch.
- [ ] Delete the assignment-edit branch after the merge.
<br><br>

## The end
This only scratched the surface of what is possible with Git and GitHub. Once you are comfortable with the command line, I would definitely encourage you to try [GitKraken](https://www.gitkraken.com). It is a great GUI for performing these tasks. 