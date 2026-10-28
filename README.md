# 考研数学 3D 几何可视化（网页版）

这是可发布到静态网站托管平台的单页网页，不需要本地 Python 服务或后端。

## 功能

- 输入方程生成曲面，包括 `z=f(x,y)` 曲面和线性竖直平面（如 `x=y`）。
- 用圆形投影域生成有界立体。
- 粘贴完整 HTML / JavaScript 页面，在隔离预览框运行。
- 粘贴 Python / Plotly 代码，在浏览器内通过 Pyodide 运行；支持 NumPy 和 Plotly。首次使用会从 CDN 加载运行时和绘图库，需要联网。代码在浏览器沙箱内运行，不会发送到网站服务器。

## 发布到 GitHub Pages

把本目录下的文件上传到一个 GitHub 仓库根目录，提交到 `main` 分支。仓库已包含 `.github/workflows/pages.yml`，会自动发布网页。仓库的 **Settings → Pages → Build and deployment** 需要选择 **GitHub Actions**。GitHub Pages 的公开网站在互联网上可访问；GitHub Free 需要使用公开仓库。

发布后网址一般为 `https://<GitHub用户名>.github.io/<仓库名>/`。如要在 Codex 中完成发布，需要连接 GitHub，并确认公开发布到目标仓库。
