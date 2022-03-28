# hello-world

## Read GitHub Documentation
[GitHub Docs](https://docs.github.com/)

### Create a new repository on the command line
```
echo "# hello-world" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/JangJinYeong/hello-world.git
git push -u origin main
```

### Push an existing repository from the command line
```
git remote add origin https://github.com/JangJinYeong/hello-world.git
git branch -M main
git push -u origin main
```