# ASM-2025-practice-git-tidy
## Overview
This repository provides some practice material to support the Reproducible Research in R workshop 
presented by [Marissa Dyck](https://github.com/marissadyck) and [Erika Barthelmess](https://github.com/erethizon) at the
2025 annual meeting of the American Society of Mammalogists.

More specifically, this is a repository designed to allow participants to learn to clone a repo, create a new RStudio
project from the repo, work with a tidy dataset, track and commit changes and push them to their own github.

## Instructions
You should already have an account on github and have git installed locally on your computer. Assuming that is the case:

Remember that, since you did not create this repository, you will not only need to clone it, but will also need to tell git where to find your own version of it on github.

To clone this repository and use it in RStudio:  


1. Create a new, empty repository on your own github account and name it the same thing as this repository (`ASM-2025-practice-git-tidy`). **DO NOT ADD A README FILE**

2. Visit the website for this repository (the one you are cloning) and find the green "Code" button **(See up above on this page!)**. Click the down arrow, and **copy** the url that is displayed under HTTPS.     
<br>     
     
<img src="Images/clone_repo.png" width=700>.    
<br>
<br>

3. **In RStudio**, choose the File menu, and then select **"New Project."** When the dialog box opens, be sure to select **"Version Control"** as your option.     
<br>

<img src="Images/create_project.png" width=500>     
<br>
<br>


4. When the Version Control dialog box opens, choose **git** as your version control method. 
<br>

<img src="Images/choose_git.png" width=500>    
<br>
<br>

5. When the next dialog box opens, **paste** the url you copied from github into the url box. You may wish to browse to a new subdirectory on your computer to create a new location for the RStudio project. If you leave "Project directory name" blank, your project will be named the same thing as the github repo.
<br>
<br>
<img src="Images/add_repo_url.png" width=500>
<br>
<br>

6. Now you need to tell git how to find YOUR empty repository (the one on your github account with the same name as this repo that you are cloning) so that you can push changes to your own repo. 

To do so, once your project has been created in RStudio,
 - open a terminal pane in RStudio if one is not already opened (Tools --> Terminal --> New Terminal).  
 - Go to YOUR github account and look at the new, empty repository that you created. Copy the URL for that new repository.
 - In the terminal pane in RStudio (and **Not in the console window**), type the following line of code, but replace `http://github.com/YOU/YOUR_REPO` with the url you copied:
 
 `git remote set-url origin http://github.com/YOU/YOUR_REPO`
 
7. Now run `git push` and see if the material you copied gets properly pushed to github.
 
## That should do it!



  
  


