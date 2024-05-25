#working directory 설정
mkdir hello-git
cd hello-git
git init
#git 설정
git remote add origin https://github.com/kartee0/hello-git-gitHub
git branch -M main
git push -u origin main
#README.md 파일 생성
vi README.md
#untracked -> staged
git add README.md
#staged -> unmodified
git commit -m "init"
#push
git push
