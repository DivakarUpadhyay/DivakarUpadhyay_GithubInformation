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
        <img src="images\DU_Git_Push.JPG">
</center>

13. Command:
      git ls-files
<center>
        <img src="images\DU_Git_GitFileInLocalRepo_11.JPG">
</center>

14. Command:
      git remote -v
<center>
        <img src="images\DU_Git_GitRemote_12.JPG">
</center>

Commands to fetch,pull and push to a subdirectory of Repository: (git version 2.28.2>)
-----------
1. Create a directory
2. git init
3. git remote add -f origin https://github.com/DivakarUpadhyay/DivakarLearningMaterial.git
4. git config core.sparseCheckout true
5. git sparse-checkout
6. git sparse-checkout set DivakarUpadhyay_JobLearningMaterials 

Format:(git sparse-checkout set directoryname which wants to fetch or checkout)

7. git pull origin master
8. git status
9. git add DivakarUpadhyay_JobLearningMaterials/DivakarUpadhyay_Technology/DivakarUpadhyay_Jquery/DIVAKAR_JQUERY_V1.md
10. git status
11. git commit -m "Initial Commits"
12. git push origin master








