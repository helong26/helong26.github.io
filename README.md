# 何龙（Long He）学术主页

本仓库用于维护何龙的个人学术主页，展示个人简介、研究方向、工作与教育经历、学术成果及相关信息。

**主页地址：[https://helong26.github.io/](https://helong26.github.io/)**

## 文件说明

| 文件或目录 | 用途 |
|---|---|
| `_pages/about.md` | 中文主页内容 |
| `_pages/about_en.md` | 英文主页内容 |
| `_config.yml` | 网站基本信息及侧边栏资料 |
| `_data/navigation.yml`、`_includes/masthead.html` | 导航配置 |
| `_layouts/` | 页面布局 |
| `_sass/` | 样式源码 |
| `assets/` | 样式、脚本及字体资源 |
| `images/helong.jpg` | 个人头像 |
| `images/favicon-zzu.ico` | 浏览器标签页图标 |

## 内容维护

- **更新主页内容**：编辑对应的中文或英文页面，保持两种语言的信息一致。
- **更新个人资料**：编辑 `_config.yml` 中的相关配置。
- **更换头像**：替换 `images/helong.jpg`，保持文件名一致。
- **更换网站图标**：替换 `images/favicon-zzu.ico`，保持文件名与格式一致。

## 构建与发布

网站基于 Jekyll，通过 GitHub Pages 自动构建和部署。

修改文件并提交至 `main` 分支后，GitHub Pages 会自动更新网站。构建及部署状态可在仓库的 **Actions** 页面查看。

发布配置为：

- **Source**：Deploy from a branch
- **Branch**：main
- **Folder**：/（root）

## 许可说明

许可条款见仓库中的 `LICENSE` 文件。
