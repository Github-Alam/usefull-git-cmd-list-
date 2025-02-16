# usefull-git-cmd-list-
list of git commend

*****How to set user info into github******
git config --global user.name "FIRST_NAME LAST_NAME"
git config --global user.email "MY_NAME@example.com"

*********How to upload any existing project into github********
git init
git add .
git commit -m "upload only"
git remote add origin https://github.com/Github-Alam/ADCperipheralCLK.git
git push origin master

****How to chabge directory***
cd name
cd .. 

***How to replace remote origin url***
git remote set-url origin <NEW_GIT_URL_HERE>
