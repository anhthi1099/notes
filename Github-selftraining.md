# GIT HUB LESSON
1. To clone a file/ folder by Github:
Use the syntax: git clone /paste the SSH links here/
For example: To clone the repo Training-Repo, go to the folderr then get the SSH key.
Next, in the command prompt or in the VS code terminal, type in **git clone git@github.com:anhthi1099/Training-Repo.git"**.

2. To check the status, commit, add, stage
* The command **git status** to check whether anything is modified or added into the repo.  
* The command **git add /name of the file/** to add the files into the stage or to make it shorter, we can use **git add .**
* To save the file, we do have to add a message too. The syntax will be **git commit -m "abc"**. The message should be descriptive to make sure the ones that edit files later will be able to catch up.

3. To push a local repo to git:
* To commence, we have to change directory to the folder we want to push. Then we initialize a file .git repo to lay foundation for the folder to be pushed by **git init**.
* Secondly, add the files by **git add .** or **git add / the file needs to be pushed/** so that the files are ready to be staged.
* Next, commit the file as guided.
* Finally, to make the computer understand the final location that the file needs to be pushed, we creat another repo on Github(under the same name of the folder on local computer), the used syntax is **git remote add origin /the SSH Link of the repo/**. Now we can push the local repo to the repo on Github by the **syntax git push origin master**.

4. To create a SSH key:
* The purpose to create a SSH key is to connect the github account to the local computer, therefore it's much easier to clone repo, make pull and push requests.
* The command is **ssh-keygen -t rsa 4096 -C "email@example.com".**
Then press enter. There would be a line to request a password. This is optional.
If you don't favor a password, continue with the "Enter".
Then the key is generate. 
Followingly, there are 2 keys generated: one is public and the other is private. Copy the public key and paste it on Github.

5. Git Branch:
* In order to check that which branch we are on, type in the terminal **git branch**
* To create another branch, type the syntax **git checkout -b featurebranch** /the branch could be renamed as wish/
*We can also use **git checkout** to switch to whichever available branch by placing the name of the branch after*
