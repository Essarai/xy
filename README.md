# XY 静态站点

一个简单的静态页面项目，包含首页、下载页和一份简历 PDF。

## 目录结构

- `index.html`: 主页
- `download.html`: 下载页
- `resume.pdf`: 简历

## 本地预览

- 直接用浏览器打开 `index.html` 即可预览
- 或在项目根目录启动一个本地静态服务器，例如：

```bash
# Python 3
python3 -m http.server 8080
# 然后访问 http://localhost:8080
```

## 部署建议

- 可直接托管到任意静态站点平台（如 GitHub Pages、Vercel、Netlify 等）
- 若使用 GitHub Pages，可在仓库设置中启用 Pages，并将分支设置为 `main`（根目录）

## 许可证

未声明许可证，如需开源请补充相应 LICENSE 文件
