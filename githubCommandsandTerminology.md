<header>
<h2 align="center">Author: Divakar Upadhyay</h1>
<h4 align="center">Date: 15th October 2022</h4>
</header>

Introduction:
-----------

commands to setup github account and upload the project on github repo:

1. command: 

    git config --list
<center>
	<img src="images\DU_Git_Img_1.jpg" alt="list" />
</center>
Set your username and Password:

2. command: 
   
    git config --global user.name "updivakar1991"
3. command:
  
   git config user.name 
<center>
	<img src="images\DU_Git_UserNameSetting_Img_2.jpg" alt="list" />
</center>

4. git config --global user.email "devupdivakar1991@gmail.com"
5. git config user.email
<center>
	<img src="images\DU_Git_EmailSetting_Img_3.jpg" alt="list" />
</center>

6. You can create a file in directory by below commands:
 touch file1.txt   (Note: It's only example)
 7. command: 
  
    git init
 <center>
	<img src="images\DU_Git_Initialization_5.JPG" alt="list" />
</center>

8. git status
<center>
	<img src="images\DU_Git_GitStatus_CheckUntrackedFile_6.JPG" alt="list" />
</center>

9. Track the file using below commands:

    a) single file:

    command:  git add file1.txt

<center>
	<img src="images\DU_Git_TrackFiles_Single_7.JPG" alt="list" />
</center>
    b) all files:
    command: git add .
    
<center>
    <img src="images\DU_Git_AllFileTrack_8.JPG">
 </center>

 10. Command:  
     git commit -m "Initial Commits"
<center>
  <img src="images\DU_Git_Commit_9.JPG">
</center>

 11. git remote add origin https://github.com/DivakarUpadhyay/DivakarUpadhyay_GithubInformation.git
<center>
  <img src="images\DU_Git_addorigin_10.JPG">
</center>
 12. Command: 
      git push -u origin master
<center>
  <img src="images\Du_Git_Push.JPG">
</center>

      








