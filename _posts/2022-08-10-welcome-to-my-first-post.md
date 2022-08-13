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
 - basic functions
---


I would first like to point out that I LOVE all feedback on the work that I do. So please if you have any comments or suggestions on any posts, feel free to offer your comments below. For this blog post I will be diving into one of my first projects I did in Data Analytics school that involved Python. I am by no means an expert in python however, enjoy learning every bit of it. 

I have attached the link to this project [here](https://github.com/Mvillarreal88/Bank-and-Polling-Python-Analysis-) for reference throughout the post. I would like to point out there are two sections of this project, one focused on assessing polling data and another on assessing bank information. For the purposes of this blog posts I will be focusing on some of the core competencies I learned early on doing this project and how it transfered over to my career growth.

When starting a .py project or even when you are using functions, think about adopting the practice of putting all imports in the functions that are using them. Now for my banking project I import in the beginning of the .py file because I know that file itself is using those dependencies. However, imagine you have multiple functions in a project that all are using different libraries inside of them. What I learned early on is to put your imports into the beginning of the functions that use them rather than the top of the module. If I ever want to move my function to another project or module, I know that the functionality will work as it has been tested in that environment. I have found this makes it easier for you to deploy functions to other projects and overall makes it easier for others to understand the dependencies that particular function is using. Now one thing you may see is that you may see a slight speed penalty however, in a lot of cases this will be minimal to insignificant.

One last thing I wanted to note on these projects is the use of f strings, and why I think they are extremely useful in a project or function. Early on for me when I was learning python, when printing out either the result of something or just using the print statement in general I found it tedious to continually have to use the + operator for other types of outputs. Now since I was self-learning I didn't know of any other options and to me it made sense, but it always looked clunky to me. Less professional and not so smooth. During the above project however was the first time in a professional setting where I found how useful the f strings could be, and for more than just eliminating the tediousness of putting the + sign over and over. It looked so much cleaner on my code, and people who are also reviewing code find it easier to follow. Admittedly I used both my old ways of  outputting with the + and utilizing the f strings in this project, but looking back now I see how important it was just to get the exposure. In my current job I had done a small presentation to some data engineers on some simple python functions and the use cases behind them. The f string was never really part of the demonstration but one of the engineers had commented "f string for the win" in the comments while I was writing the output. That stuck with me. For me this was first nature when producing an output, to others the utilization of f strings may not be a first option.


Thank you for reading and please provide feedback as it helps me professionally develop and the blogs will be healthier with engagement. It doesn’t have to be in the comments below if you don’t want to, send over a message on LinkedIn. This was my first blog post of any kind and really hope you enjoyed the read. 


[1]: http://www.jacobtomlinson.co.uk/
