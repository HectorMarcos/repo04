# Repo 04

## NoFastForwardTest

```
mkdir repo04
cd repo04
touch readme.md
git init
git add .
git commit -m "first commit"
git remote add origin https://github.com/HectorMarcos/repo04.git
git branch -M main
git push -u origin main
```

```
git branch "noFFTest"
git checkout noFFTest
code .
git commit -am "readmemd modified"
git push origin noFFTest
git checkout main
git merge --no-ff noFFTest
git push origin main

```
