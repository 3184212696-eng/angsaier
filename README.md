# 篮球知识库网站上传包

这个文件夹已经是可直接上传到 GitHub、再用 Vercel 发布的网站包。

## 你只要做这几步

### 1. 新建 GitHub 仓库
在 GitHub 网页里新建一个仓库。

### 2. 上传这个文件夹里的全部文件
把下面这些文件上传到仓库根目录：
- index.html
- 404.html
- vercel.json
- README.md

### 3. 去 Vercel 导入这个 GitHub 仓库
在 Vercel 里：
- Add New
- Project
- 选择你的 GitHub 仓库
- 直接 Deploy

### 4. 等它部署完成
部署成功后，Vercel 会给你一个 `xxxx.vercel.app` 的网址。
这个网址就是你的小伙伴可以直接访问的网站。

## 以后怎么更新
如果以后知识库有新版本：
1. 用新的 `index.html` 替换仓库里的旧 `index.html`
2. 提交到 GitHub
3. Vercel 会自动重新部署

## 说明
- 这是纯静态网站，不需要数据库，不需要后端
- `404.html` 用来保证直接访问异常页面时仍有内容
- `vercel.json` 是给 Vercel 的静态配置文件
