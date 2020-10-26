---
layout: default
parent: Application Development Standards
title: 1.1. Use a modern distributed version control system
nav_order: 1
---

# Why is this a standard?

In this digital age, automation is becoming more of a necessity than a luxury. As progress is made towards adopting cloud, containers, and in the future being serverless, it becomes essential to add automation and adopt DevOps practices. 

It becomes increasingly difficult to add automation, increase collaboration and adopt modern practices while choosing to store your application code in a centralized version control systems such as subversion(SVN).

# What does this standard mean?

Application development teams:

##### 1.1.a. should use modern distributed version control systems such as git, github, gitlab or bitbucket

##### 1.1.b. should use github for opensource code

##### 1.1.c. should use enterprise installations of git such as GitLab or Bitbucket for code that cannot be opensource

##### 1.1.d. should enable the use of multifactor authentication for all users accessing the code repository

##### 1.1.e. should use 'bcgov' org while storing opensource code in github

##### 1.1.f. should use [github flow](https://guides.github.com/introduction/flow/) or [git flow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow) to manage version control

##### 1.1.g. should ensure master/main branch contains the code currently running in production

##### 1.1.h. should use relevant branch protection mechanisms to ensure the master/main branch cannot be deleted or modified without a pull request

# How can you meet this standard?

If you are deploying a new service, consider to opensource your code and choose GitHub as your version control system.

If you are currently using subversion, irrespective of whether you are planning to lift and shift your application, move your source code to GitHub or Bitbucket based on whether you can opensource your code or not.
A sample script to move from Subversion to Bitbucket is given [here](assets/scripts/SVNtoBitbucket.sh).


