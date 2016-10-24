# GitHub Tutorial

_by **Zele Dong**_

---
## Git vs. GitHub
* _Git_ is used to store data of folders and files as backups.
* _Github_ is used to keep track of the changes made to folders and files.
* While _Github_ requires _git_ to function,_Git_ does not require _Github_ to function.  
 

---
## Initial Setup
#### In order to create a github account,you'll have to do the followings,  
1. Relocate yourself to github by typing github.com in the URL  
2. Click on the SignUp Icon on the top right land side of the webpage.  
3. Type in your own Username,Email Address,and Password.  
4. Choose either one of the personal plan that you want.  
5. Check off the points that you think are appropriate for yourself.  
6. Then Click `Create Account`,now you can create a SSH key between Github and c9.  
7. Click on settings in the top right profile icon.  
8. Go to SSH and GPG keys by clicking on the leftsidebar.  
9. Create a new SSH key and give it an appropriate name.  
10. Copy the SSH key,then go to c9 and click on the top right gear icon,paste the SSH key at where it says SSH key.  


---
## Repository Setup
#### In order to create,edit,and upload the files,you'll need to do the followings,  
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
  
#### Git Status
* `Git Status` is used to check whether changes were made to a file within the repository.When you type and enter `Git Status` on the command line, the file name appears in red indicating the file was modified/edited,while the file name appears in green indicating the file is already added to the staging area.  
* Before typing `git status`,you should be in the correct repository.Otherwise, move to the repository by using `cd`.When you're in the right repository,you would simplely type `git status` on the command line to check the status of the files.  
  
#### Git Add
* `Git Add` is used when adding a file to the staging area.When you make changes to a file,you would add the modified file to the staging area in order to commit and save it as a `snapshot`.  
*   `git add` is only needed when you want to add modified file/files,that is not already in the staging area,to the staging area.Be sure to double check by typing `git status` on the command line,if the file names appear in red then you're free to type `git add [file name]` to add the file to staging area.  
  
#### Git Commit
* `git commit` is used to permanently save the files added to staging area as `snapshots`.You could always check the `snapshots` by typing `git log` on the command line.
* When committing files in the staging area,you'll need to include a brief message that will remind yourself what you've done to the files.To do this,you type `git commit -m "Where You Type The Message"`.  
  
#### Git Push
* `git push` is used to upload the committed files from your local repository to the remote repository,this would help you restore the files if the file were lost in any occasion.(The remote repository would be the one you created on Github in this case)  
* When you're using `git push` for the first time,you'll need to include the remote name;origin,and the branch name;master.For instance,the correct syntax is `git push -u origin master` when making the connection between the local and remote repository,then you'll just simplely type `git push` to upload the committed files.