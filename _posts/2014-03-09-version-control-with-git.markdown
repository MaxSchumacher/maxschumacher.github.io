---
layout: post
title:  "Version Control with Git!"
date:   2014-03-09 13:19:47
categories: jekyll update
---

There are plenty of resources on Git it is a very powerful tool, that you have to learn the basics of in order to be productive.

Git was developed by Linus Torvalds to manage the Linux Kernel codebase as he was unhappy with other Version control systems such as Subversion.

Git is a version control system that allows you to track changes in the code you edit (and revert them) and also to collaborate with other developers on the same codebase. In combination with a code - repository hosting service such as Github, Git is very powerful.

To check whether you have Git installed on your machine run

<code>git -v </code> which is short for <code>git --version </code>

displays whether you have a version of git installed. If not, run <code>sudo apt-get install git</code> to install it.

As soon as you have a project you're working on, you need to set up an account at Github (you could go to other companies such as Bitbucket) but we'll stick to Github because it developed to a kind of showcase of ones work. Hosting Public repositiories is free anyway and Github just works fine.

In your project folder run:

<code>git init</code> to initialize the directory. Now run <code>git status</code> to get an overview of what Git has done.

For Git to track your changes you have to add these new files/folders to the tracking which you accomplish with <code>git add "Filename"</code>

 As you've worked with Git, you probably tried those same aliases and been given an error that it was not a git command. Its true that Git doesn't ship with all of those aliases, but it does give you a better option. You can add your own aliases via the git config.

To add git ci as a shortcut to git commit, just type git config --global alias.ci "commit" the command prompt. This works for any Git command so you can customize your environment just the way you want it. 

