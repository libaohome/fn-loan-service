git config --global user.name "libaohome"
git config --global user.email "libaohome@163.com"
<!-- git remote add origin https://libaohome:key@github.com/libaohome/fn-loan-service.git -->

git remote set-url origin https://libaohome:key@github.com/libaohome/fn-loan-service.git
git remote -v

git add .
git commit -m "Initial commit"
git branch -M main
git push -u origin main