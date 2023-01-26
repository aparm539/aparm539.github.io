---
title: 'Basic Git Guide'
date: 2023-01-24
permalink: /posts/2023/01/Basic-Git-Guide/
tags:
  - Git
  - Introductory
---

### What is Git?

A google search for “git” might lead you to <a href="https://git-scm.com">git-scm.com</a>. A website created and maintained by members of the Git community. The description they provide is short: 

>Git is a free and open-source distributed version control system designed to handle everything from small to very large projects with speed and efficiency

I’ll be honest, when I first read the explanation above, I didn’t understand it. I will try and make that description a little more digestible. 

### What is Version Control? 

Version control is keeping track of all the changes made to files or programs.

This makes it easier to:
-	Collaborate with others on code.
-	Understand why changes were made to a program.
-	Find out who made those changes.
-	Find out when your code stopped working as intended.

But how does Git make all that possible? Let’s dive deeper into how you will use Git and GitHub at school to find out.

### What is GitHub?
A website that can be used to host repositories online.

### What is a Repository?
The folder on your computer where you coding project is stored. 

### So What Does Git Do? 

Every time you save a file in git it takes a snapshot of the respository. In other words git basically takes a picutre of what all your files look like at that moment and stores a reference to that snapshot. If nothing has changed git doesnt store the file again and just keeps the old copy. 

<img src="https://git-scm.com/book/en/v2/images/snapshots.png">

### What Will We Use Git and Github For?

You will use Git and Github to recieve and submit assignments for your classes. Let's go through how to do these things. 

**Note:** This guide assumes you have installed Git and connected it with your GitHub account.
{: .notice}

### Cloning an assignment

1. In Terminal navigate to the folder where you will be storing your assignments.

    **Note:** This should not be your desktop or your downloads folder. Create a dedicated folder for each of your programming classes where you will  store your assignments and projects.
    {: .notice}

    <!--
    Code for video tag taken from:
    Cazzulino, D. (2021, July 23). How to embed videos in GitHub Pages without growing the repository size. Daniel Cazzulino. Retrieved January 23, 2023, from https://www.cazzulino.com/github-pages-embed-video.html 
    -->
    
    <video src="https://user-images.githubusercontent.com/113143064/214609279-cd67a4b2-3d4a-4c92-b8a0-09114c0ac075.mov" controls="controls" style="max-width: 550px;"></video>

2. In your browser find the GitHub page for your assignment. Click on the green code button and copy the HTTPS link.
 
    **Note:** The link to the GitHub page for your assignment will usually be on D2L. You need the link you get after clicking the green button **not** the one at the top of your browser.
    {: .notice}

    <video src="https://user-images.githubusercontent.com/113143064/214609461-10c9165f-431d-4cae-9d7a-45c5c714a379.mov" controls="controls" style="max-width: 550px;"></video>

3. Return to your Terminal and run the following command:
   
    `git clone "url you copied after clicking the green button"`

    <video src="https://user-images.githubusercontent.com/113143064/214609542-ff1954c8-e368-43ac-a2dc-b170a951cdcf.mov" controls="controls" style="max-width: 550px;"></video>


4. You can check and see that the folder has been created on your computer.

    <video src="https://user-images.githubusercontent.com/113143064/214609657-4b1699f0-dbe6-4160-bc94-6c38e10c5b7d.mov" controls="controls" style="max-width: 550px;"></video>

    That's all! The assignment is now on your computer and you can work on it! 

### Uploading an assignment to Github

1. Open Terminal and navigate to the folder where your assignment is saved:

    

2. Type in the following command: 
   
    `git status`

    You should see the files you have modified in red. 



3. Next stage all the files you have changed using the command:

    `git add .`
    
    **Note:** If you only need to add a specific file, you can do so with the following command: `git add "file you want to add"`

4. Commit the staged changes using the command:   

    `git commit -m "Description of changes made"`

    The `-m` portion of the command stands for message. Make sure to include a descriptive message of what changes you have made.  

5. Sync the changes wih GitHub using the following command: 

    `git push`

Thats it!

You can return to the GitHub page for the repository in your browser and view the changes.  



<!--git config: Edits git configuration on your user profile

git clone: Download a copy of a repository to your local computer

git status: Show the current state of the git repository

git add: Add new files or changes to existing files to the staging area to be committed

git commit: take a snapshot of the current state and store it with a message

git pull: Retrieve changes from a remote repository

git push: Send changes to a remote repository

Chacon, S., &amp; Straub, B. (2014). Pro Git. git-scm. Retrieved January 23, 2023, from https://git-scm.com/book/en/v2 
-->



