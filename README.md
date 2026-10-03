# 王腾 · 成长档案

我的个人网站，记录科研、数学建模、项目实践，以及学习之外的生活。

**在线访问：[printf-wt.github.io](https://printf-wt.github.io/)**

## 关于我

中南林业科技大学计算机与数学学院 2024 级本科生，关注连续变量量子通信、数学建模与编程实践。希望这里既能展示成果，也能留下从问题到思路、从验证到实现的过程。

## 网站栏目

| 栏目 | 内容 | 页面 |
| --- | --- | --- |
| 科研经历 | 论文、研究方向与阶段进展 | `research.html` |
| 竞赛经历 | 按时间倒序整理的竞赛记录和证书 | `competitions.html` |
| 项目经历 | 项目简介、技术栈与 GitHub 仓库 | `projects.html` |
| 日常生活碎片 | 学习之外的照片与日常记录，逐步补充 | `life.html` |
| 经验总结 | 科研、建模和编程中的思考，逐步补充 | `notes.html` |
| 关于我 | 个人简介、成长历程与联系方式 | `about.html` |

## 实现与部署

网站使用 HTML、CSS 和少量原生 JavaScript，各栏目为独立页面，适配电脑与手机。无需后端、数据库或构建工具，通过 GitHub Pages 发布。

- `index.html`：首页，展示个人简介。
- `style.css`：全站样式。
- `site.js`：手机导航菜单交互。
- `*.png`、`*.pdf`：公开展示的竞赛证书。
- `wechat-qr.jpg`：联系方式中的微信二维码。
- `.nojekyll`：让 GitHub Pages 直接发布静态文件。

## 本地预览

在仓库根目录运行：

```bash
python -m http.server 8000
```

打开 <http://localhost:8000>。页面使用以 `/` 开头的站内路径，建议通过本地 HTTP 服务预览。

## 内容维护

1. 编辑对应栏目的 HTML 文件；更新个人简介时，同步修改 `index.html` 和 `about.html`。
2. 有明确日期的经历按时间从新到旧排列；参赛时间和获奖时间分别说明。
3. 新增图片或证书后，检查页面中的文件路径和替代文本。
4. 提交到 `main` 分支后，GitHub Pages 会自动更新，可在 Actions 中查看部署状态。

发布来源为 **Settings → Pages → Deploy from a branch → main → / (root)**。

## 证书与隐私

公开证书已对其他人的姓名等信息进行遮挡。后续上传证书时，也请先处理他人姓名和不宜公开的个人信息；只提交处理后的文件，原件不放入公开仓库。

## 联系方式

- GitHub：[printf-wt](https://github.com/printf-wt)
- Gmail：[wangteng0052@gmail.com](mailto:wangteng0052@gmail.com)
- 学校邮箱：[wangteng@csuft.edu.cn](mailto:wangteng@csuft.edu.cn)
- 微信：见网站「关于我」页面。
