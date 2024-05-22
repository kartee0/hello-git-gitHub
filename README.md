mkdir hello-git
cd hello-git
git init
git remote add origin https://github.com/kartee0/hello-git-gitHub
git branch -M main
git push -u origin main
vi README.md
git add README.md
git commit -m "init"
git push
