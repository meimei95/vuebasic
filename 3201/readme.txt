git add <filename>   (注:filename是文件名）

或者git add .       （注：后面的.是把项目文件夹里面的文件都添加进来）

------这是 git 基本工作流程的第一步；使用如下命令以实际提交改动

git commit  -m  "代码提交信息"  （注："代码提交信息"里面换成你需要，如“python apitest”）

    ----你的改动已经提交到了 HEAD，但是还没到你的远端仓库。

git push -u origin master   （注：是把本地仓库push到github上面，此时需要输入你的github帐号和密码）
