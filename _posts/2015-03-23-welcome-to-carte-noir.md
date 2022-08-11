---
layout:     post
title:      Welcome to My first blog post
date:       2022-08-10
author:     Matthew Villarreal
summary:    Learning and utilizing tips and tricks in python early in my career
categories: Python
thumbnail:  
tags:
 - Python
 - importing libraries
 - file pathing
 - basic functions
---

Welcome to my first blog post!

I would first like to point out that I LOVE all feedback on the work that I do. So please if you have any comments or suggestions on any posts, feel free to offer your comments below. For this blog post I will be diving into one of my first projects I did in Data Analytics school that involved Python. I have attached the link to this project [here](https://github.com/Mvillarreal88/Bank-and-Polling-Python-Analysis-) for reference.

I would like to point out there are two sections of this project, one focused on assessing polling data and another on assessing bank information. For the purposes of this blog posts I will be focusing on some of the core competency's I learned early on doing this project and how it transfered over to my career growth.

When starting a .py project or even when you are using functions, think about adopting the practice of putting all imports in the functions that are using them. Now for my banking project I import in the beginning of the .py file because I know that file itself is using those dependencies. However, imagine you have multiple functions in a project that all are using different libraries inside of them. What I learned early on is to put your imports into the beginning of the functions that use them rather than the top of the module. If I ever want to move my function to another project or module I know that the functionality will work as it has been tested in that environment. I have found this makes it easier for you to deploy functions to other projects and overall makes it easier for others to understrand the dependencies that particular function is using. Now one thing you may see is that you may see a slight speed penalty however, in alot of cases this will be minimal to insignificant.


[1]: http://www.jacobtomlinson.co.uk/
