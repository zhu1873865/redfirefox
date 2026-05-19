# Redfirefox Personal Website

个人简历网站，适合部署到 GitHub Pages。

## 文件结构

```text
index.html
assets/avatar.png
README.md
```

## 推送命令

```bash
git clone https://github.com/zhu1873865/redfirefox.git
cd redfirefox
# 把 index.html 和 assets 文件夹复制进来
git add .
git commit -m "add personal website"
git push
```

## GitHub Pages 设置

Repository → Settings → Pages → Build and deployment → Source 选择 `Deploy from a branch`，Branch 选择 `main` / root。
