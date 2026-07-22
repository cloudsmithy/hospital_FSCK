# 医院用药记录 · 自我疗愈

> 程序员的医学笔记 —— 个人用药记录与整理。

一个基于 [Jekyll](https://jekyllrb.com/) + [minima](https://github.com/jekyll/minima) 主题的静态站点，托管在 GitHub Pages。

🔗 **在线阅读**：https://cloudsmithy.github.io/hospital_FSCK/

## ⚠️ 免责声明

本站内容仅为个人记录与整理，**不构成任何医疗、诊断或用药建议**。任何用药请务必遵从医生或药师指导。

## 目录结构

```
.
├── _config.yml          # Jekyll 站点配置（theme: minima 2.5.1）
├── index.md             # 首页（layout: home，自动列出文章）
├── about.md             # 声明页（顶部导航）
└── _posts/              # 用药记录，文件名须为 YYYY-MM-DD-标题.md
    ├── 2026-07-22-骨科-氟比洛芬凝胶贴膏.md
    └── 2026-07-22-泌尿-左氧氟沙星.md
```

## 新增一条用药记录

在 `_posts/` 下新建文件，文件名格式为 `YYYY-MM-DD-标题.md`，内容示例：

```markdown
---
layout: post
title: "科室 - 药品名"
date: 2026-07-22
categories: 科室
---

正文……
```

## 本地预览

```bash
bundle install
bundle exec jekyll serve
# 浏览器打开 http://localhost:4000
```

## License

内容版权归作者所有；站点代码结构可自由参考。
