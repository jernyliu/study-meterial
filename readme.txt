Git commit -m "..message.."
如果发现注释需要修改，那么按下字母键c就会进去vim编辑器
修改好之后，按下ESC,退出编辑转态，然后连按两次大写字母Z，就可以保存退出。

git 命令：
git init
git add readme.txt
git commit -m "...."
git status仓库当前的状态
git log
git log --pretty=oneline
git reset --hard HEAD^回退到上一个版本
git reset --hard HEAD^^回退到上上一个版本
git reset --hard HEAD~100回退到上第100个版本
git reset --hard 1094a回退到commit id为1094a的版本
     版本号没必要写全，前几位就可以了，Git会自动去找。当然也不能只写前一两位，因为Git可能会找到多个版本号，就无法确定是哪一个了。

cat readme.txt查看readme.txt中的内容