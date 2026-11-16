# 网页发布与维护

在线地址：https://pc-cccc.github.io/my-course-notes/

目录页为仓库根目录的 `index.html`，样式已经写在文件里，不需要安装软件或构建。修改后提交到 `main`，由 GitHub Pages 自动发布。

## 首次配置

在仓库 **Settings → Pages** 中设置 **Deploy from a branch → main → /(root)** 并保存。`.nojekyll` 用于跳过 Jekyll 处理。

## 以后更新

- 调整目录、课程介绍和链接：编辑 `index.html`。
- 添加笔记：上传文件，再在目录页补充对应的相对链接。
- 原来的 3 份 PDF 和 `ML Interaction.html` 保留原名、原位置，原有链接才能继续使用。
- 保持 README 简短，较长的课程说明放在目录页。

提交后，在 **Actions** 中查看 Pages 发布结果。如果网页尚未更新，等待发布完成后刷新。

本地预览可以直接打开 `index.html`。PDF 与交互页面需放在同一目录。

[GitHub Pages 官方设置说明](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
