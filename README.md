# 1. 初始化本地git仓库
git init

# 2. 创建README.md
echo "# my-first-project" >> README.md

# 3. 加入暂存区
git add README.md

# 4. 本地提交
git commit -m "first commit"

# 5. 绑定远程仓库（你的这个链接，已经写好）
git remote add origin https://github.com/Tanjingfeng1/my-first-project.git

# 6. 因为建仓库时勾选了自带README，必须先拉取合并
git pull origin main --allow-unrelated-histories

# 7. 推送到GitHub
git push -u origin main
