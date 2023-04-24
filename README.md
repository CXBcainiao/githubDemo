# githubDemo
a github demo

# 文档发生了修改,需要添加一些注释,提交到本地仓库
git init
git add .
git commit -m "xxx"
git status

# 建立远程仓库连接
git remote -v
git remote add origin 地址
git remote -v

# 获取远程仓库信息
git fetch
git branch
git merge --allow-unrelated-histories

# 发送给远程
git pull

# 给本地建立新的分支dev
git checkout -b dev