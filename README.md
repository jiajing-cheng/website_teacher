# 🎓 极简风家教介绍主页

这是一个基于纯静态技术构建的极简风格家教个人介绍网站。专为移动端通勤场景优化，采用大字号排版与高对比度设计，确保在地铁等单手滑动场景下的极致阅读体验。

> 🚀 **在线预览**：[点击https://jiajing-cheng.github.io/website_teacher/ 访问 GitHub Pages 演示]

---

## ✨ 核心特性

- **📱 移动端优先**：针对 375px 宽度深度优化，CTA 按钮垂直堆叠，拇指热区友好。
- **🎨 极简美学**：参考 Apple 留白与 Stripe 卡片阴影，高对比度 WCAG AA 级无障碍标准。
- **⚡️ 零依赖**：纯 HTML5 + CSS3，无 JS 框架，无外部字体库，首屏加载极速。
- **📐 响应式布局**：CSS Grid 智能折叠，完美适配 375px / 768px / 1440px 三端。
- **🔗 原生交互**：电话 `tel:` / 邮箱 `mailto:` 一键唤起，内联 SVG 图标零请求。
<img width="2400" height="962" alt="1" src="https://github.com/user-attachments/assets/8fde5a74-dfb7-4516-aafd-290458d83d39" />
<img width="2378" height="1166" alt="2" src="https://github.com/user-attachments/assets/2da6a74e-c7f9-47e6-b4ec-96c111806f3c" />

---

## 📂 项目结构

```text
.
├── index.html              # 首页 (Hero区 + 功能导航 + 底部联系方式)
├── works.html              # 学生作品展示页
├── notes.html              # 教学札记/博客页
├── credentials.html        # 资质荣誉/信任背书页
├── css/
│   └── style.css           # 全局样式与 Design Tokens
├── images/                 # 存放首屏图片、作品图等静态资源
│   └── (your-images.jpg)
└── README.md               # 项目说明文档

