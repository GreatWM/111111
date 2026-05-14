# c-language-demo
git remote add origin https://github.com/GreatWM/c-language-demo.git
git remote -v
git push -u origin main
echo "// 新增代码注释" >> test.c
git add test.c
git commit -m "再次修改test.c文件"
git push
git pull origin main
git fetch origin
git merge origin/main
