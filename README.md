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

-----3rd exp 
git config --global.username "amulya008-ag"
git config --global.email "amulyag008@gmail.com"

create a repository 

git clone <github rep url>
cd git-lab-demo
git init
git remote add origin <github repos url>
git pull origin master
git add .
git commit -m "Add main.py file"
git push origin master

git fetch origin
git merge origin main
git pull



---4th exp 
git clone <git url> 
cd Git_PullRequests
touch file1.txt
echo "This file is created in master branch" > file1.txt
git status
git add file1.txt
git push origin main
git pull origin main 
git branch feature-1
git checkout feature-1
echo "This change is from feature-1 branch" >> file1.txt
touch feature.txt
echo "Feature branch file" > feature.txt
git status
git add .
git commit -m "Changes done in feature-1"
git push origin feature-1

1. Open GitHub repository
2. Click Compare & Pull Request
3. Base branch → master
4. Compare branch → feature-1
5. Add description
6. Click Create Pull Request

git checkout main 
git pull origin main 
git log --online
git branch -d feature-1
git push origin --delete feature-1


--5th exp
git clone <>
cd Git_tagging
ls
git pull
git tag v1.0
git tag
git tag -a v1.2 -m "v1.2 Tag created"
git tag
git show v1.0
git tag -l "v1.*"
git push origin v1.0
git tag v2.0
git push --tags

git tag -d v1.0
git push origin -d v1.0


--7th exp
jenkins create new item
In Build Step click on Add build step
Select Execute Windows Batch Command and type -- echo "Hi, Welcome to Jenkins"
and console output 


8th exp 
 javac BankService.java
 java BankService

