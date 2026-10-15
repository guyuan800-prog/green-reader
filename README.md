# 小圆阅读器（保留原版排版）

本版本以原始 `阅读器.html` 为基础，保留原有顶部栏、正文区域、底部设置栏、配色和阅读操作方式；在原有界面中增加书架和章节目录按钮，并附带 PWA 部署文件。

## GitHub Pages 部署
1. 将本文件夹里的全部文件上传到 GitHub 仓库根目录。
2. 主页面必须命名为 `index.html`。
3. 仓库 Settings → Pages → Build and deployment，选择 `Deploy from a branch`。
4. 选择 `main` 分支和 `/(root)` 目录后保存。
5. 等待发布后，通过 GitHub Pages 提供的网址访问。

## 说明
- 原版阅读器功能和整体排版尽量保持不变。
- 新增书架用于保存多本已导入小说，章节目录会尝试识别常见章节标题。
- 阅读内容和进度保存在当前浏览器本地；请定期导出或另行保存原始小说文件。
- PWA 需要 HTTPS 或 localhost；DOCX 解析依赖 Mammoth CDN，离线时可能无法解析新文件。
