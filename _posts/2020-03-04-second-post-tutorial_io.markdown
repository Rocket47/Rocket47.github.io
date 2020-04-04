---
layout: post
title:  "Easy way to start on the github.io"
description: Second post :)
date:   2020-04-03 22:58 +0530
---
### Instruction and issues

Hi everyone!

So, this instruction for windows user but for unix it will be easy, as always :)

First of all:

* Need to create a repository [GitHubPages](https://pages.github.com/)

* 	I decided to use [Jekyll]( https://jekyllrb.com/)  (Actually, it was first tool which have been found me.)
	
	* Please install ruby gems [official site](https://rubyinstaller.org/)
	* So, next step we should put the [certificate](https://gist.github.com/agragregra/53d8b9cc22c3f14d6ad6dc536c66fe14) in a folder
	##### Example on my PC C:\Ruby27-x64\cacert.pem 
	* Please check  ruby -v и gem -v (Run CMD as administration)
    * Set sertificate use the command
	##### set SSL_CERT_FILE=C:\Ruby27-x64\cacert.pem
	
***
How to install jekyll environment

* gem install jekyll
* jekyll -v
* gem install bundler

***
How to create a project

* create a folder Site anywhere on the disk (run CMD from this plaсe)
* jekyll new YourBlogName
* jekyll build
* jekyll s
* Good job! Your blog is available to link localhost:4000
* If you want to stop server just send CTRL+C in console

***

How to create a new post

* So, you can find all your *.md or *.markdown files in the folder _posts
* Pattern for file name  year-month-date-name.md. 
* Example: 2020-03-04-second-post-tutorial_io.markdown
* To publish just add the file to the folder _post. 
* Jekyll himself will collect everything you need.

***
Design of your blog

There are many predefined themes and templates for Jekyll.

* You can find some [jekyllthemes](https://rubyinstaller.org/)
* To assemble the template you need to unzip it, start the console from the template folder and drive in the familiar jekyll build.

***
Remark
* But not any of these templates can be uploaded to GitHub and even assembled on your computer
* Just try to use simple themes.
* I spent some time finding the right one. Perhaps this was the main issue

***
Posting on GitHub.

* We already have the repository login.github.io
* Clone this repository and put filies form your root foolder of the blog