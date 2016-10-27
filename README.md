# GitHub Tutorial

_by < Paola Chamorro >_

---
## Git vs. GitHub

* The difference between Git and GitHub is that  
    * **Git** is a version control that runs in the commandline , it allows you to track and save changes in a project .
    * **Github** is the site that allows you to store these changes remotely for later viewing 
* They both work with each other in order to keep track of changes, but while Git allows you to keep track of changes within your local repository , Github holds these changes in a remote repository .  


---
## Initial Setup

* In order to make a github account you need to sign up using your current email and a password which can be easily remembered . 
    * After you have created your account on github , github will want to verify your accounts authenticity through an email that you need to reply to in the steps directed . 

* In github and c9.io , the SSH key is used to connect the accounts and allow a smooth interchangable use of both accounts. In order to set up this connection you need to go into your github account and go into settings in order to find the tab that displays `SSH and GPG keys` , you will click on this tab and name it . Afterward , you will go into your c9 account , click on your personal icon and paste the code given for your key in github into the `SSH keys` in . 
* In github, an SSH key is also used when cloning or downloading another users project . This key is used so that your account on github is remembered each time you go to work into the users project . The use of this key takes away the burden of having to verify your account every time you go to work inside of the other users project.
    * ![](https://preview.c9users.io/paolac8171/github-learning/pr-practice/Screen%20Shot%202016-10-24%20at%201.32.15%20PM.png)
 
---
## Repository Setup
 
* In order to setup a repository on your c9 account, you begin by going into your home directory through the use of `cd ~/workspace` . Then you can create your repository through the use of `mkdir` , which you add with your repositories name , for example, `mkdir first-repo` . Afterward, you want to go into your repository through the use of `cd first-repo`. 
* Your next steps are to initialize git within your repository . By intializing git, you are in a sense , turning on the program that allows you to save the changes you make within a directory. 
    * _Command syntax_ 
        * ![](https://preview.c9users.io/paolac8171/github-learning/pr-practice/Screen%20Shot%202016-10-24%20at%208.40.00%20AM.png?_c9_id=livepreview0&_c9_host=https://ide.c9.io)
* Once you have made changes within the files of your repositories , you want to **add** these changes to the staging area . By adding these changes to the staging area , you are preparing them to be commited.
    *  _Command syntax_
        * ![](https://preview.c9users.io/paolac8171/github-learning/pr-practice/Screen%20Shot%202016-10-24%20at%208.47.43%20AM.png?_c9_id=livepreview0&_c9_host=https://ide.c9.io)
* After you have added the changes made to your file to a staging area , then you can **commit** these changes. By commiting a change your are deciding to permanentley add it to your files 'final showcase' . 
    * _Command syntax_
        * ![](https://preview.c9users.io/paolac8171/github-learning/pr-practice/Screen%20Shot%202016-10-24%20at%208.48.52%20AM.png) 
*These changes which you have saved in your local repository , c9.io , can be saved on the cloud through the use of a remote repository . This remote repository can store the changes made on your local repository for later viewing.

* While in github , one way you can create a new remote repository is by clicking on the top left corner , where you'll find a plus sign , which will open up a menu that shows you the option to create a repository. 
    * ![](https://preview.c9users.io/paolac8171/github-learning/pr-practice/Screen%20Shot%202016-10-24%20at%201.35.05%20PM.png)
    * You'll want to name this repository the same name that you have subjected it to in your local repository.
        
        * ![](https://preview.c9users.io/paolac8171/github-learning/pr-practice/Screen%20Shot%202016-10-24%20at%201.35.17%20PM.png) 
 
---
## Workflow & Commands

* **Git status** is a command that is used in order to check up on your ongoing commands and see what files you have added changes to and what changes you added to the staging are and/ or commited. It is very important as an organizational tool because it allows you to keep track of your work within the commandline.
    * _Command syntax_
        * ![](https://preview.c9users.io/paolac8171/github-learning/pr-practice/Screen%20Shot%202016-10-24%20at%208.50.38%20AM.png)
* **Git add** is when you add a files changes to the staging area . By doing this you are preparing the changes made within the file to be commited.
    * _Command syntax_ 
        * ![](https://preview.c9users.io/paolac8171/github-learning/pr-practice/Screen%20Shot%202016-10-24%20at%208.47.43%20AM.png?_c9_id=livepreview0&_c9_host=https://ide.c9.io)
* **Git commit** is a command used when you are trying to permanentley add  a files changes to what can be called a files 'final product'. 
    * _Command syntax_
        * ![](https://preview.c9users.io/paolac8171/github-learning/pr-practice/Screen%20Shot%202016-10-24%20at%208.48.52%20AM.png)
* **Git push** is when you push up the changes made to a file from your local repository to your remote repository to be stored . 
    * _Command syntax_
        * ![](https://preview.c9users.io/paolac8171/github-learning/pr-practice/Screen%20Shot%202016-10-24%20at%208.51.06%20AM.png?_c9_id=livepreview1&_c9_host=https://ide.c9.io)
---
## Eror handling
* When dealing with the initializing of git within the wrong directory , you want to use the command `rm -rf .git` , which un-initializes a directory which has been initialized.
* When trying to remove a repository within your local repository you want to navigate to ~/workspace , and then use the command `rm -rf repo-name` in order to remove the repo . 
    * When trying to remove a remote repository you want to navigate to the repository you are trying to delete within github and then go into the settings within the repository action bar . There you can find a Danger Zone where you will find the option to delete the repository.
    







