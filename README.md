# a


1st exp
mkdir Git_Lab_Experiment1
cd Git_Lab_Experiment1
git init
ls
ls -a
git config --global.username "amulya008-ag"
git config --global.email "amulyag008@gmail.com"
echo "hello guys" > README.txt
git status
git add .
git status
git commit -m "Initial commit"
echo "good morning" >> README.txt
git status
git add .
git commit -m "Updated README file"
git log

2nd exp
git init
git branch
git branch feature-branch
git checkout feature-branch
ls
git status
git add .
git status
git commit -m "File 1 modified"
git checkout master
git status
git add .
git commit -m "File 1 modified for conflicts"
git status 
git merge feature-branch
git mergetool

hit enter it will open tortoise merge tool
Right click on Mine- File1_local_1083 and select 3rd option (use block from
right before left)

Click on Save button

git status
git add .
git commit -m "File1 Merged"
git log --oneline 



