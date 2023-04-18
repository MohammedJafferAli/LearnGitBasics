# LearnGitBasics
The purpose of this repo is used for storing basic Java and Selenium codes and for git &amp; github learning purpose

Refer the url given below to learn the basic of Git Commands and for this you don't need any external tools

URL : https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html


Step by step explanation to use Git and Github

1. Download the latest version of Git from the official website based on the OS
  https://git-scm.com/downloads
2. Execute and install the git (Local repo) application in your machine
3. Best practise to create a new folder in your local before pushing it to central repo (Ex. GitLocalFiles) 
4. Open CMD prompt and start entering the following commands
    i.    git config --global user.name "Jaffer"  
    ii.   git config --global user.email "Jaffercharliebe@gmail.com"
    iii.  Change directory to the local folder cd Foldername (ex. cd GitLocalFiles)
    iv.   Enter git init -> Create a local repo (A new file .git should be added to the same folder)
5. There are multiple stages in pushing codes to Remote repo
6. First stage push your file/codes to staging  
    i.  git add * -> Adding all the files to staging     , if you want to add specific file then use git add <filename> make sure its a same folder
    ii. git status -> check the status of the staging
![image](https://user-images.githubusercontent.com/61991616/232758078-393e8628-840a-4450-958f-c590b31f61e0.png)
![image](https://user-images.githubusercontent.com/61991616/232758192-277bd64f-f513-4899-ae22-3ac1e32855c1.png)
![image](https://user-images.githubusercontent.com/61991616/232758452-08d9fa25-90b0-471b-bbf8-a394f005c8b3.png)
7. Adding remote repo and pusing the committed codes/files 
