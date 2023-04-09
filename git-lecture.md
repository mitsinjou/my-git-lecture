# Setup of a Github Repository

## 1-create a new repository on the command line

### In the working Directory (you want to track)

### (shell)

echo "# my-git-lecture" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:mitsinjou/my-git-lecture.git
git push -u origin main

## 2- push an existing repository from the command line

### In the working Directory pwd (you want to track)

### (in the shell)

git remote add origin git@github.com:mitsinjou/my-git-lecture.git
git branch -M main
git push -u origin main
