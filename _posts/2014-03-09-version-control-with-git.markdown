---
layout: post
title:  "Version Control with Git"
date:   2014-03-09 13:19:47
categories: jekyll update
---
---
layout: post
title:  "Version Control with Git"
date:   2014-03-09 13:19:47
categories: jekyll update
---

There are plenty of resources on learning Git. it is a very powerful tool, that enables collaboration between software developers and allows you to track the changes made to your source code, whether you work in a project or not.

Git was developed by Linus Torvalds to manage the Linux Kernel codebase as he was unhappy with other Version control systems such as Subversion or Mercurial.

Git is the most commonly used Version Distributed VersionControl System for projects with Rails.

To check whether you have Git installed on your machine, open your terminal with "Ctrl + t" and run

<code>git --version </code>

if you get output similar to:

git version 1.9.0

you're fine. Else run:

<code>sudo apt-get install git</code> to install it with the aptitude package manager, which is the default package manager on Ubuntu.

For a first time setup run:

<code>git config --global user.name "Your Name"</code>

and

<code>git config --global user.email "your_email@example.com"</code>

In order to have nice colors in your terminal run:

<code>git config color.ui true</code>

As soon as you have a project you're working on, it is helpful to set up an account at Github (or other repository hosting services.)

We'll stick to Github because it evolved  into a kind of showcase of one's work, it is not uncommon to show your Github profile in a job interview. Hosting Public repositiories is free anyway and Github just works quite seamless.

No need to reinvent the wheel, work through this short Git introduction by Github to learn more:

Follow this interactive course "Try Git":

https://www.codeschool.com/courses/try-git

Here's a slighty more advanced and visually appealing Guide to go through:

http://rogerdudler.github.io/git-guide/

After that you might want to spend some time with this little project: Git Branching:

http://pcottle.github.io/learnGitBranching/

You can save some time by setting up Aliases for Git:

To add git <code>ci</code> as a shortcut to <code>git commit</code>, just type git <code>config --global alias.ci</code> "commit" the command prompt. This works for any Git command so you can customize your environment just the way you want it. 

Salesforce and Heroku created a Cheatsheet, which is a handy reference for the most common commands.

https://na1.salesforce.com/help/pdfs/en/salesforce_git_developer_cheatsheet.pdf
 

