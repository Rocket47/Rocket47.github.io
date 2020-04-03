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

* gem install jekyll
* jekyll -v
* gem install bundler

***

* create a folder Site anywhere on the disk (run CMD from this plaсe)
* jekyll new YourBlogName
* jekyll build
* jekyll s
* Good job! Your blog is available to link localhost:4000
* If you want to stop server just send CTRL+C in console

***

How to create a new post

* So, you can find all your *.md or *.markdown files in the folder _posts



