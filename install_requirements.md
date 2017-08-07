---
title: "Install Prerequisite for Workshop"
author: "John Little"
date: "`r Sys.Date()`"
output: html_document
---

To complete the hands-on portion of the workshop you'll need software pre-installed.  Due to the nature of the workshop we will not have time to troubleshoot installations during the workshop.  Please be sure to perform the following steps **on the laptop you will bring to the workshop**.

## Required Software

**Download and install**.  I recommend accepting the install defaults for the following:

- **git** https://git-scm.com/downloads

    1. ![](images/git_os.png "Click on the link to your OS") 
    1. Run the install and accept all the defaults
    
- **R** http://archive.linux.duke.edu/cran/

    - If you have not installed R before, choose *install R for the first time*
    - If you already have R installed on your workstation, I recommend running the latest version but any reasonably current version should be fine.  The latest version is R-3.4.1
    
- [**RStudio**](https://www.rstudio.com/products/rstudio/download/#download) `https://www.rstudio.com/products/rstudio/download/#download`

    - ![](images/rstudio_download.png "Click *Download Rstudio Desktiop*")
    
- If you haven't yet, install each of those programs


## Verify your Access to **Duke's** GitLab

During the Workshop we will use [Duke's Gitlab](https://gitlab.oit.duke.edu) implementation.  To complete the hands-on portion of the workshop, you **must log-in** -- **in advance** of the workshop -- and ensure you have NetID access to https://gitlab.oit.duke.edu.  If you do not have access to **Duke's** gitlab, [contact OIT](https://oit.duke.edu/help).

- Be certain you login via "Duke Shibboleth Login" using your NetID

    - ![](images/gitlab_shib_login.png)  

## Genearte SSH keys in Advance of the Workshop

I recommend generating your SSH keys in advance of the workshop.  To do so, you should have already installed git to your laptop.  Then follow these instructions for generating the keys.  We will cover key configuration in the workshop and [I recommend following the steps on **Generating a new SSH key pair**](https://gitlab.oit.duke.edu/help/ssh/README) **in advance** of the workshop.

1. To begin, open a shell **from RStudio**

    1. In RStudio > Menubar > `Tools > Shell...`
    
1. Follow the instructions https://gitlab.oit.duke.edu/help/ssh/README
1. Close the Shell
        



