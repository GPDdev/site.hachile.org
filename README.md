# The Hachile Project

<div align="center"><img alt="Checks: browser verified" src="https://img.shields.io/badge/checks-browser%20verified-blue"><img alt="License: MIT" src="https://img.shields.io/badge/license-MIT-green"><img alt="Version: 1.16.2" src="https://img.shields.io/badge/version-1.16.2-lightgrey"><img alt="Language: HTML and CSS" src="https://img.shields.io/badge/language-HTML%20%2F%20CSS-orange"></div>

[访问网站](https://site.hachile.org/)

## 目录

- [介绍](#介绍)
- [本地预览](#本地预览)
- [维护](#维护)
- [参与贡献](#参与贡献)
- [许可证](#许可证)

## 介绍

这是 Hachile 站群的目录页，以一棵树串联个人身份、创作、社群和档案。纸色底纹、原创植物线稿和分枝式目录构成页面主体，静态页面托管在 GitHub Pages。

- **枝叶**：25 个站点按四组分枝排列，树上的分组文字可直接跳转到相应目录。
- **根**：保留 Hachile 关于身份、连接、连续性与数字化的宗旨。
- **年轮**：展示最近五次更新，使用原生折叠区域保留全部历史日志。

页面仅使用 HTML、CSS 和本地 SVG，支持手机、键盘导航与减少动态效果的系统偏好，关闭 JavaScript 仍可完整浏览。

## 本地预览

不需要安装依赖。在仓库根目录运行：

```sh
python -m http.server 8000
```

打开 [本地预览](http://localhost:8000/)。没有构建步骤，也不需要运行时 JavaScript 或外部字体服务。

## 维护

| 文件 | 用途 |
| --- | --- |
| `index.html` | 分组入口、站点目录、宗旨和更新日志 |
| `style.css` | 纸张与植物主题、响应式布局及键盘焦点样式 |
| `assets/hachile-tree.svg` | 首页树形插画 |
| `assets/roots.svg`、`assets/rings.svg`、`assets/leaf.svg` | 树根、年轮和站点图标 |
| `CNAME` | GitHub Pages 自定义域名 |

更新日志与 [Home](https://home.hachile.org/#changelog) 使用相同版本号和内容。新增网站时，将名称、简介和入口加入对应的 `.branch-sites`，并更新目录中的站点数量。新增日志放入 `.recent-releases`，超过五条的记录移入 `.history`，保留已有历史内容。

发布前检查 320、390、768、1024 和 1440 像素宽度下的页面，确认没有横向溢出；检查四个树上入口、所有站点地址、图片加载，以及使用 Tab 和 Enter 展开历史记录的行为。GitHub Pages 从 `main` 分支根目录发布。

## 参与贡献

欢迎通过 [Issues](https://github.com/GPDdev/site.hachile.org/issues) 报告失效入口或说明错误。

## 许可证

页面代码使用 [MIT License](LICENSE)。
