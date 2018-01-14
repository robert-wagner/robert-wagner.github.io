---
layout: post
title:  "Welcome to Jekyll! (aka We have a Blog)"
date:   2017-12-21 19:41:03 -0500
categories: jekyll update
---
My website is switching to Jekyll. Among other things Jekyll makes it easier to create a blog so this is the beginning of the first post. This post will later detail my process of switching over.

# Getting Started with Jekyll and GitHub Pages 

GitHub Pages (where this blog is hosted) allows you to very easily integrate Jekyll into your build process. Jekyll is a static site generator which compiles markdown files into html. If you ever have had the pleasure of writing blog posts in raw html, you will know why this is of a benefit, however to illustrate here is the markdown to genereate the first part of this blog post
`Markdown code`
On the other hand, here is the html
`html code`
As you can see, the markdown is much more friendly to write.

With the benefit of ease of writing in mind, migrating to Jekyll could begin.

GitHub has a guide for setting up a repository for using Jekyll, however this guide glosses over a few steps which ended up being serious pain points during my switch to Jekyll.

To start the GitHub guide has you check to see if you have ruby installed, this can be done by running the command
`which ruby`
Most unix based systems will have ruby installed already (mine did), however if it is not installed you can install it using 
`sudo apt-get install ruby`

This however was where my first pain point occurred. To develop locally with ruby you also need the ruby-dev package which is not mentioned in the GitHub guide at all. It can be installed with
`sudo apt-get install ruby-dev`

