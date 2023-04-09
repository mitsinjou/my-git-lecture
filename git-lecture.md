# create a new repository on the command line

## In a Directory:

**(shell)**

echo "# my-git-lecture" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:mitsinjou/my-git-lecture.git
git push -u origin main


# push an existing repository from the command line

## In a Directory:

**(shell)**

git remote add origin git@github.com:mitsinjou/my-git-lecture.git
git branch -M main
git push -u origin main
