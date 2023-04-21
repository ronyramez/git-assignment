#1
git init
git remote add https:github.com/ronyramez/git-assignment.git-assignment.git

#2
touch .gitignore
vim .gitignore
*~
*.swp
.DS_Store
git add .gitignore
git commit -m ",gitignore file is made"
git push origin IT 101 A5

#3
git checkout -b text-files
touch file1.txt file2.txt file3.txt
vim file1.txt
This is file1.txt
vim file2.txt
This is file2.txt
vim file3.txt
This is file3.txt
git add file1.txt file2.txt file3.txt
git commit -m "fil1.txt , file2.txt , file3.txt are done"
git push orgin text-files

#4
