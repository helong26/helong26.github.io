# 何龙（Long He）学术主页

基于 [孙泽敏主页原仓库](https://github.com/zeminsun166/zeminsun166.github.io) 修改，保留原 Jekyll 模板、页面布局、顶部导航和中英文切换。

## 内容维护

- `_pages/about.md`：中文首页。
- `_pages/about_en.md`：英文页面。
- `_config.yml`：站点名称、邮箱、头像、部署地址等。
- `_data/navigation.yml` 与 `_includes/masthead.html`：导航配置。
- `images/helong.jpg`：从何龙提供的 PDF 中提取的本人照片。
- `images/favicon-zzu.ico`：浏览器标签页图标，使用[郑州大学官网校徽](https://www.zzu.edu.cn/zzu.ico)。

个人资料以所提供的《吉林大学-博士-何龙.pdf》和用户后续补充为依据。现任单位为郑州大学，职称为初聘副教授；教育经历包括吉林大学博士（2023.09—2026.07）、新加坡科技设计大学联合培养（2025.02—2026.02）、吉林大学硕士（2021.09—2023.07）及成都理工大学本科（2015.09—2019.07）。联系方式位于研究方向下方，包含微信 HL-6635、邮箱和电话；中英文同步。详情列出 9 篇论文、4 项科研项目、5 项发明专利、10 条荣誉奖励及 6 种期刊的审稿服务；简介中的成果总数按用户最新提供的完整文字填写。论文链接使用不含临时访问参数的 IEEE 文献地址；INFOCOM 论文的 2024 年份由 IEEE 记录补充核对。

未提供何龙的 Google Scholar、GitHub 或 ORCID 账号，因此个人资料链接留空，已停用原作者的引用数据抓取，并清除原作者的统计与站点验证配置。保留论文和专利中作为合作者出现的孙泽敏姓名。

## GitHub Pages

当前正式网址为 https://helong26.github.io/，已通过静态文件发布。线上仓库包含生成的 `index.html`、`.nojekyll` 与 `LICENSE`；本目录保留完整 Jekyll 源码用于后续维护，源码修改后需重新生成并更新线上静态文件。

将本目录的文件放入指定仓库根目录，沿用现有 GitHub Pages 发布配置即可。当前 `_config.yml` 的 `url` 为 `https://helong26.github.io`，`repository` 为 `helong26/helong26.github.io`。无需修改源代码即可显示各栏目。

本地使用 Ruby/Bundler 时运行：

```sh
bundle install
bundle exec jekyll serve
```

中文首页 `/`，英文页 `/en/about/`。仓库保留原模板的 MIT 许可。
