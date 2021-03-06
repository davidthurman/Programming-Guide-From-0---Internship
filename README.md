# From Zero to Internship Ready

## Introduction

I have tought several people how to become internship ready in software development without any prior knowledge on the topic. My methodology revolves around creating several projects that will build up your portfolio. By the end of this guide, you will have what is required to get an internship in either web development or app development. 


## Step 1: Python

<p align="center">
  <img src="/images/pythonLogo.png?raw=true" alt="Python Logo"/>
</p>

### Why Python?

Whether your goal is to develop apps or websites, I recommend learning the basics of Python. Python is a general purpose programming language which means it can be used in many different situations. You can develop desktop applications with it like a word processor (think Microsoft Word) or a calculator. You can also use Python can also be used to build websites. Some big examples of this include Instagram, Pinterest, and the NASA website.


### Where to Begin

To start learning the basics of Python, I usually refer people to this free course on Udacity:

https://www.udacity.com/course/programming-foundations-with-python--ud036

It is a very good introduction to programming for people with no background knowledge. The course also walks you through a few small projects that you can add to your portfolio such as:

1. a program to draw shapes on the screen
2. a program that sends texts to your phone
3. a program to display your favorite movies in a website that also allows you to watch the trailers

### Extra Projects:

1. Write a script that tells the user which number is greater. The project should run like so:
```
Enter number one:
>132
Enter number two:
>93
Number one is greater
```

2. Try building a calculator in a Python script. The project should run like so:
```
Enter number one:
> 17
Enter number two:
> 3
Add(add), Subtract(subtract), Multiply(multiply), or Divide(divide)
> add
20
```

Now that you have learned the basics of your first programming language, it's time to move onto the foundations of website building.

#### Want more Python?

If you want to dive further into Python, check out this great book that walks you through building several major projects in Python:

https://www.amazon.com/Python-Crash-Course-Hands-Project-Based-ebook/dp/B018UXJ9RI/ref=sr_1_1?ie=UTF8&qid=1491667373&sr=8-1&keywords=python



## Step 2: HTML and CSS:

<p align="center">
  <img src="/images/htmlAndCss.png?raw=true" alt="HTML Logo and CSS Logo"/>
</p>

### Why HTML and CSS?

As with Python, I think HTML and CSS are important skills to have as a software developer regardless of whether you want to build apps or websites. HTML and CSS are the foundation of any website you see and as a developer, you are expected to be familiar with them.

### What are they?

If you were to think of a website as a house, HTML would be the structure of the house (the walls, doors, roof, etc) and CSS would be all of the things that decorate the house (paint, pictures, decorations, etc). HTML lays out the underlying structure of a website while CSS adds style to the site.

### Where to Start?

When it comes to HTML and CSS, my favorite reference site is w3schools.com. They have everything you might need to know for basic web development and the site works as a great cheat sheet. 

To start with HTML, I recommend starting here and completing w3schools tutorial:
https://www.w3schools.com/html/default.asp

*Note*: W3schools mentions text editors in its tutorial. Personally, I would recommend installing Sublime Text 3 as your go-to editor. It is made for programmers and allows for easy readibility of many types of programming languages:
https://www.sublimetext.com/3


And once you have a basic understanding of HTML, go ahead and start the CSS tutorial as well:
https://www.w3schools.com/css/default.asp

*Note*: Do not feel discouraged if you are not able to absorb everything when going through the tutorials. The purpose of going through them is to get a basic understanding of how the two languages work together and not to retain every piece of information you read.


### Projects:

1.Build a website that displays your favorite movies and tv shows. Each poster should link you back to the movie/tv show's IMBD site.

<p align="center">
  <img src="/images/myFavoriteMediaProject.png?raw=true" alt="Media Project"/>
</p>

#### Want More HTML and CSS?

My personal favorite book on HTML and CSS would have to be: 

<p align="center">
	<a href="https://www.amazon.com/HTML-CSS-Design-Build-Websites/dp/1118008189/ref=sr_1_1?ie=UTF8&qid=1492876018&sr=8-1&keywords=html+and+css">
  		<img src="/images/htmlAndCss.jpg?raw=true" alt="HTML and CSS Book" width="500px"/>
  	</a>
</p>



This is a great book to have for reference no matter your skill level and it provides almost anything you could need in HTML or CSS with easy to read examples.

## Step 3: Javascript:

<p align="center">
  <img src="/images/javascriptLogo.png?raw=true" alt="Javascript Logo"/>
</p>

### Why Javascript?
Javascript is reponsible for all of the moving parts of a website and knowing it is a requirement for any web developer. 

### What is it?
If we continue with the same house analogy I used to explain HTML and CSS, Javascript would be all of the moving parts of your house such as your lights, electronics, temperature, etc. Almost any website you come across on the web will contain at least some Javascript.

### Where to Start?

As with HTML and CSS, I always use w3schools for most things Javascript related. You can start by going through their tutorial at:
https://www.w3schools.com/js/default.asp

### Want More Javascript?

The makers of the HTML and CSS book I had recommended also made a great book on Javascript and JQuery (We will get to JQuery soon):

<p align="center">
	<a href="https://www.amazon.com/JavaScript-JQuery-Interactive-Front-End-Development/dp/1118531647/ref=sr_1_1?ie=UTF8&qid=1492905184&sr=8-1&keywords=javascript+and+jquery">
  		<img src="/images/javascriptAndJquery.png?raw=true" alt="Javascript and JQuery Book" width="200px"/>
  	</a>
</p>

## Other Resources:

### Git/Github:

<p align="center">
  <img src="/images/githubIcon.png?raw=true" alt="Github Logo"/>
</p>

#### What is it?

Github is a website that people upload software projects to in order to share and/or work collaboratively on. If you upload a project to Github, other developers can view your projects and your code. If they think it would be a good idea to change or add something, they could pull down your code, make their changes, and upload it back up to you. From there you can either accept the changes or deny the request. 

#### Why do we need it?

For our purposes, Github will act as a portfolio page for potential recruiters and employers to see your projects. Every project you work on will be uploaded to Github for people to see.

#### Where to start?

I recommend checking out this video for learning the basics of Github:

https://www.youtube.com/watch?v=SWYqp7iY_Tc

#### Cheat Sheet:

##### From your terminal/command line:

<b>General Commands to Know</b>:

<p align="center">
  <img src="/images/terminalPic.png?raw=true" alt="Github Logo"/>
</p>

```git
cd  *destination*
```

Change your current directory 

Example:
```git
cd Desktop/WebProjects 
```
Change the current directory to Desktop/WebProjects
```git
cd .. 
```
Go back one directory (if you were in Desktop/WebProjects and input "cd .." you would then be in Desktop)
```git
pwd
```
Shows current working directory



<b>Git Commands</b>:

<b>*When you first upload a repository*</b>:

```git
git init 
```
Initiates the current working directory with a git repository
```git
git add . 
```
Adds all files in this directory to your repository
```git
git commit -m "Commit message" 
```
Creates a commit with the current changes to upload. Anything in the parenthesis is a commit message describing the changes

```git
git remote add origin *github repository url* 
```
Sets the local repository to look at the repository on Github you created

```git
git push --set-upstream origin master 
```
Pushes the changes to your online repository


<b>*When you make changes to a current repository*</b>:

```git
git add . 
```
Adds all files in this directory to your repository

```git
git commit -m "Commit message" 
```
Creates a commit with the current changes to upload. Anything in the parenthesis is a commit message describing the changes

```git
git push
```
Pushes the changes to your online repository