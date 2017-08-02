---
title: "Git Workshop - Hands-on Outline"
author: "John Little"
date: "August 2, 2017"
output: html_document
---
# git and a git host

## Overview; What is

1. git

    - lost in the forest -
    
        - ![](https://twoknobbytires.files.wordpress.com/2012/05/img_4829.jpg) [^https://blog.twoknobbytires.com/category/iowa-mountain-biking-trails/]
    - breadcrumbs
    - repository
1. GitHub and GitLab and Bitbucket
1. Duke's GitLab
1. Markdown  (see Keep.google notes)
1. Orchestrating with RStudio

	- Masks the CLI
	- Easier to get started
	- PowerUsers can still use commands  

## Hands-On:  a quickstart

### Generate SSH Keys (Do this once per workstation)

- https://gitlab.oit.duke.edu/help/ssh/README  

### Make a Repository
1. Duke's GitLab -- https://gitlab.oit.duke.edu
1. Duke Shibboleth Login
1. New Project
1. Add a project name:  `test-one` > Create Project

    - Notice command line instructions.  Could come in handy  
1. Make a README file (click the README link)  > `Commit changes`
1. Make a license file (click the LICENSE link) 

	- click *Appply a license format* > choose *The Unlicense* (or paste in a Creative Commons License) > `Commit changes`  
1. Make a .gitignore file (click the .gitignore link)

    - click *Apply a .gitignore format* > choose *R* > `Commit changes`  
1. Bring the repo down locally via RStudio

	1. Back at your GitLab repo `https://gitlab.oit.duke.edu/<<your-NetID>>/test-one`, copyURL to clipboard (click icon)
	1. Launch RStudio, Menubar:  *File > New Project* > Version Control > Git > paste the URL from the step above into *Repository URL:*

### Edit your Repo in RStudio

1. In the Files Pane, Open the README.md file
1. In the Editor Pane, modify your README with [Markdown](https://en.wikipedia.org/wiki/Markdown#Example)

    - 

## Resources

- [RMarkdown Cheatsheet](https://www.rstudio.com/wp-content/uploads/2016/03/rmarkdown-cheatsheet-2.0.pdf)
- 