---
layout: post
title:  "Easy way to start on the github.io"
description: Second post :)
date:   2020-04-03 22:58 +0530
---
### Instruction and issues

Hi everyone!

So, this instruction for windows users but for unix it will be easy, as always :)

<mark>STEP 1 : First of all:</mark>

* Need to create a repository [GitHubPages](https://pages.github.com/)

* I decided to use [Jekyll]( https://jekyllrb.com/)  (Actually, it was first tool which have been found me.)
	

    1) Please install ruby gems [official site](https://rubyinstaller.org/)

    2) So, next step we should put the [certificate](https://gist.github.com/agragregra/53d8b9cc22c3f14d6ad6dc536c66fe14) in a ruby folder
  
    3) Example on my PC ***C:\Ruby27-x64\cacert.pem*** 
  
    4) Please check  ***ruby -v и gem -v*** (<mark style="background-color: lightblue">run CMD as administration</mark>)
  
    5) Set sertificate use the command ***set SSL_CERT_FILE=C:\Ruby27-x64\cacert.pem***

	
***
<mark>STEP 2 : How to install jekyll environment</mark>
```
 cmd: gem install jekyll
 cmd: jekyll -v
 cmd: gem install bundler
```
***
<mark>STEP 3 : How to create a project</mark>

* Create a folder ***Site*** anywhere on the disk (<mark style="background-color: lightblue">run CMD from this plaсe</mark>)
```
cmd: jekyll new YourBlogName
cmd: jekyll build
cmd: jekyll s
cmd: CTRL+C //stop server
```
* Good job! Your blog is available to link ***localhost:4000***

***

<mark>STEP 4 : How to create a new post</mark>

* You can find all your ___*.md___ or ___*.markdown___ files in the folder ***_posts***
* Pattern for file name  ***year-month-date-name.md*** 
* To publish a new post just add a file to the folder ***_post*** 

***

<mark>STEP 5 : Design of your blog</mark>

***Jekyll has many design templates***

* Some of them can be found here [jekyllthemes](https://rubyinstaller.org/)
* Start the CMD and send ***jekyll build***

***
<mark style="background-color: lightblue">Remark</mark>
* But not any of these templates can be uploaded to GitHub and even assembled on your computer
* Just try to use simple themes.
* I spent some time finding the right one. Perhaps this was the main issue

***
<mark>STEP 6 : Posting on GitHub.</mark>

* We already have the repository ***login.github.io***
* Clone this repository and put filies from your root folder of the blog
* Great news! Your blog is created on the GitHub Pages