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
   git remote add origin <server location>
  ex.  git remote add origin https://github.com/MohammedJafferAli/LearnGitBasics
  
  ![image](https://user-images.githubusercontent.com/61991616/232760997-dda9da86-95e1-4dd1-a8fa-35a51faf8c13.png)
  
  You have successfully connected your remote repo with the local repo, now it's time to push all the codes to remote repo and branch is master by default
  
8. git push origin master

![image](https://user-images.githubusercontent.com/61991616/232761605-87b7ceb9-2b8a-4def-ae4d-75b053940f25.png)

!!! If you are pushing your codes to remote repo for the very 1st time it will ask credentials to connect , use the same credentials that used to create the repo !!!


![image](https://user-images.githubusercontent.com/61991616/232761887-c2287102-9d90-493e-8cef-a5abf8e70d84.png)


![image](https://user-images.githubusercontent.com/61991616/232762104-d95d103e-b94e-49f0-8cc5-bb01778074db.png)

![image](https://user-images.githubusercontent.com/61991616/232762143-ce92b47d-fb93-4e66-b00d-842a4fae7cf7.png)

![image](https://user-images.githubusercontent.com/61991616/232762233-d6cc6a04-aaa2-40ec-a5b3-4507c84b560d.png)
