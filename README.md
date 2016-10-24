# GitHub Tutorial

_by **Zele Dong**_

---
## Git vs. GitHub
* _Git_ is used to store data of folders and files as backups.
* _Github_ is used to keep track of the changes made to folders and files.
* While _Github_ requires _git_ to function,_Git_ does not require _Github_ to function.  
 

---
## Initial Setup
In order to create a github account,you'll have to do the followings,
1. Relocate yourself to github by typing github.com in the URL
2. 


---
## Repository Setup
In order to create,edit,and upload the files,you'll need to do the followings,  
1.  Create a new directory using `mkdir`.  
2.  `cd` into the directory just created.  
3.  Login to Github and create a new repository on Github,the name of this new repository must be the same as the directory you just created.  
4.  After creating this new repository on Github,you'll see a quick setup provided by Github.There will be two lines of commands under "…or push an existing repository from the command line",copy the lines of commands,then paste and enter them on the command line one at a time.  
5.  Type `git init` inside of the correct folder.(This turns the directory into a repository)  
6.  Create a new file using `touch`.  
7.  Open the file with either one of the following **two** methods.  
    * Double click on the file in c9.  
    * Type `c9 [name of the file with extensions]`   
8. Edit/make changes to the file   
9. Check the changes made to the file by typing `git status`.If the name of the file is in **red**,then you'll have to type `git add` to add it.  
10. Once the file name appears in **green** in `git status`,you're free to type `git commit` to commit it.You wanna make sure to include a message,a message that reminds you want you've done to the file, to yourself or other people.  

---
## Workflow & Commands
