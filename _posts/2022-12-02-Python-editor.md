---
toc: true
layout: post
description: Using Python to Create a basic Text Editor
image: images/Rich-Text-Editor-Toolbar-sm.png
categories: [python,software development]
title: Python Editor
---

### Background


>*Time spent thinking about doing something takes away the time you have to actually do it.*

Having read the above words of advice on my Instagram feed, I decided to research interesting things to do when you have a lot of time to spend. I somewhat had an idea that I wanted to do something related to computers, maybe read about some new technology or try learning a new programming language. While browsing the internet, I came across an interesting YouTube video title "Python Project Create Real Software". 

I have been using python for scientific computing on Google Collaboratory for my university courses but have never had the opportunity to use this powerful language to create something. So keeping in mind the above quote, I jumped right into 'creating' this project.


> I am writing this blog as an experience of mine and not a review per se. I appreciate the [content creator](https://www.youtube.com/watch?v=wRIUnHO_6KY) for his efforts and give him full credit for the coding aspect of the project.


### Pre-requisites:

- Basic Knowledge of Python:  Basic data structures like lists, tuples, dictionaries, etc. Some knowledge of tkinter - Graphical User Interface (GUI) package that is bundled with Python, Some experience with object oriented programming is beneficial but not necessary

- A very versatile text editor (ironic that one needs one to build one :D) like Visual Studio Code (VSC), Atom, Sublime or any editor of your choice. I personally prefer VSC since it has myriad extensions to make your life easy


- Willingness to learn something new, there are instances where it gets a bit repetitive while defining functionality for various features in the editor and one may feel the need to simply copy-paste those sections from the [source code](https://github.com/Shlok2002/Brief---Text-Editor.git) but do remember that doing so does hamper one's learning

### Features of the Text Editor:

- A toolbar which houses the **Bold**, *italic*, alignment options and other basic text editing features 

- A status bar for counting words and characters

- The new file, open, save, save-as, exit functionalities common to most applications.

- Multiple colour themes


### Experience

I decided to name my text editor *Brief* , a name shared by a once-popular programmer's text editor in the 1980s and early 1990s.


The prerequisite knowledge helped me in grasping the concepts explained in the video quite easily. The content delivered was simple and to the point with little to no shift from the main goal of the tutorial i.e. coding a text editor. In my personal opinion, a Python novice too can easily build this software with a bit of extra effort. 

The great thing about this tutorial is that towards the end, the creator walks you through the process of taking the python script and converting it into a executable (.exe), which can be placed on your desktop and may replace a basic text editor. I would personally recommend using *pyinstaller* package rather than the  *cx_freeze* package to make an executable. Pyinstaller is easier to use and does not requires a lot of effort. Just remember to use the correct flags to generate your desired outputs.


A few screenshots of the editor:

**First screen**
![first.jpg](https://cdn.hashnode.com/res/hashnode/image/upload/v1621079869023/_-619hUpb.jpeg)

**Dark Theme**


![dark.jpg](https://cdn.hashnode.com/res/hashnode/image/upload/v1621079967126/M9JO1yGUa.jpeg)





### Scope for improvement


- 
The bold, italic and underline buttons can have their functionality improved by incorporating selective highlighting.


- 
Functionality to add tables and charts in the editor.


- 
Functionality to export the .txt files to other extensions.



I thoroughly enjoyed coding the program and would be actively looking to code similar programs in the near future. I will share my experiences via this blog.


### Resources
-
[Source Code](https://github.com/Shlok2002/Brief---Text-Editor.git)

-
[Youtube Video](https://www.youtube.com/watch?v=wRIUnHO_6KY)

-
[Pyinstaller Package ](https://pypi.org/project/pyinstaller/)


-
[VSC Download](https://code.visualstudio.com/download)

-
[My GitHub](https://github.com/Shlok2002)







































