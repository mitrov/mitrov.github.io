---
layout: post
title: GitHub Pages + Jekyll + Kate 
author: "Džoka Mitrov"
categories: journal
tags: [general]
comments: false
---
Before you get to write anything you have to decide on what platform your blog will be and / or which software you use for running the blog. Since I see my blog as an experiment I decided NOT to do a lot of research and just go with whatever seems attractive. After 5 mins (2 mins more likely) of googling and looking at other blog sites I decided to stick with this combo:

[GitHub Pages](https://pages.github.com/) and [Jekyll](https://jekyllrb.com/)

GitHub Pages made sense to me since I'm alredy familiar with GitHub. The workflow of editing and pushing to live seems natural. And because GitHub Pages is deeply integrated with Jekyll I decided to give it a try. However, as a developer working on a Win10 notebook I was not happy reading this:

> While Windows is not an officially-supported platform, it can be used to run Jekyll with the proper tweaks.

Nope. I'm not interested in tweaking around to get some blog software running. Out of curiosity I tried the installation via Bash on Windows 10. Installing Jekyll was easy. But editing the same files in Win10 and the Windows Subsystem for Linux seemed like asking for trouble. File changes were not recognized by the Jekyll server and encoding issues came up. Yes, if you spend enough time to tweak around the different tools you can probably get it to work.

So I decided to go all-in with a clean Ubuntu on a new virtual machine and everything seems to work fine now. I run 'jekyll serve' to start a development server at http://localhost:4000. 
I edit the Markdown files using [Kate](https://kate-editor.org/) and Jekyll automatically (re-)generates the content as soon as I save the file I'm editing. 