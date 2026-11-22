# The Hachile Project

<div align="center"><img alt="Tests: manual checks" src="https://img.shields.io/badge/tests-manual%20checks-blue"><img alt="License: MIT" src="https://img.shields.io/badge/license-MIT-green"><img alt="Version: 1.10.15" src="https://img.shields.io/badge/version-1.10.15-lightgrey"><img alt="Language: HTML and CSS" src="https://img.shields.io/badge/language-HTML%20%2F%20CSS-orange"></div>

[访问网站](https://site.hachile.org/)

## 目录

- [介绍](#介绍)
- [本地预览](#本地预览)
- [维护](#维护)
- [参与贡献](#参与贡献)
- [许可证](#许可证)

## 介绍

这是 Hachile 站群的目录页，集中展示各站点的访问入口和更新日志。静态页面托管在 GitHub Pages。

## 本地预览

不需要安装依赖。在仓库根目录运行：

```sh
python -m http.server 8000
```

打开 http://localhost:8000/。

## 维护

| 文件 | 用途 |
| --- | --- |
| `index.html` | 站点目录和更新日志 |
| `style.css` | 页面样式 |
| `CNAME` | GitHub Pages 自定义域名 |

更新日志与 [Home](https://home.hachile.org/#changelog) 使用相同版本号和内容。新增网站时，同步更新目录中的入口与介绍。

## 参与贡献

欢迎通过 [Issues](https://github.com/GPDdev/site.hachile.org/issues) 报告失效入口或说明错误。

## 许可证

页面代码使用 [MIT License](LICENSE)。
