# 我的家乡 - 金泽古镇

<div align="center">

![金泽古镇](images/logo.svg)

**江南第一桥乡 · 上海青浦金泽镇**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Responsive](https://img.shields.io/badge/Responsive-Yes-brightgreen)](https://web.dev/responsive-web-design-basics/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

[在线演示](#) | [特性介绍](#-特性) | [快速开始](#-快速开始)

</div>

---

## 📖 项目简介

本项目是一个响应式静态网站，以"我的家乡"为主题，展示了上海市青浦区金泽镇的独特风貌。金泽镇被誉为"江南第一桥乡"，拥有深厚的历史文化底蕴。网站通过现代化的设计和技术实现，呈现了金泽古镇的古桥文化、水乡景色及民俗风情。

### 🎯 项目亮点

- 📱 **完美响应式**：适配 PC、平板、手机三种设备
- 🏛️ **丰富内容**：8个页面详细介绍金泽六座古桥及阿婆茶文化
- 🎨 **现代设计**：简约优雅的UI设计，符合江南水乡气质
- ⚡ **流畅交互**：平滑滚动、动画过渡、悬停效果
- 📝 **语义化代码**：遵循 W3C 标准，注释完整

---

## ✨ 特性

### 🎨 设计特色

- **配色方案**：深水蓝 (#003366) + 古金色 (#c5a059)
- **字体系统**：西文 Segoe UI + 中文衬线字体
- **视觉效果**：卡片悬停动画、图片缩放、渐变背景

### 📱 响应式设计

| 设备类型 | 屏幕宽度 | 布局特点 |
|---------|---------|---------|
| 🖥️ PC端 | ≥ 1330px | 三列网格布局，固定导航栏 |
| 📱 平板端 | 768px | 两列网格布局，汉堡菜单 |
| 📱 移动端 | 480px | 单列布局，全屏菜单 |

### 🏗️ 技术栈

- **HTML5**：语义化标签（header、nav、main、section、article、footer）
- **CSS3**：
  - Flexbox / Grid 布局
  - CSS Variables（自定义属性）
  - Media Queries（媒体查询）
  - Transitions / Transforms（过渡与变换）
- **JavaScript**：
  - 原生 ES6+
  - DOM 操作
  - 事件监听
  - 平滑滚动

---

## 📂 项目结构

```
212240148-zhuweijie/
├── index.html                  # 主页
├── puji-bridge.html            # 普济桥详情页
├── wanan-bridge.html           # 万安桥详情页
├── yingxiang-bridge.html       # 迎祥桥详情页
├── ruyi-bridge.html            # 如意桥详情页
├── tianhuangge-bridge.html     # 天皇阁桥详情页
├── linlao-bridge.html          # 林老桥详情页
├── apocha.html                 # 阿婆茶文化页
├── css/
│   ├── style.css               # 主样式表（响应式）
│   └── bridge-detail.css       # 详情页样式
├── js/
│   └── main.js                 # 交互脚本
├── images/
│   ├── logo.svg                # 矢量 Logo
│   ├── logo.jpeg               # 网站图标
│   ├── fengmian.jpeg           # 主页封面
│   ├── *-bridge-*.jpg          # 古桥图片
│   └── apocha*.jpg             # 阿婆茶图片
├── fonts/                      # 字体文件夹（预留）
├── README.md                   # 项目说明（英文）
└── README.txt                  # 作品说明（中文）
```

---

## 🚀 快速开始

### 在线预览

直接使用浏览器打开 `index.html` 文件即可预览。

### 本地运行

```bash
# 克隆项目
git clone https://github.com/你的用户名/jinze-ancient-town.git

# 进入项目目录
cd jinze-ancient-town

# 使用任意 HTTP 服务器运行（可选）
# Python 3
python -m http.server 8000

# Node.js (需要先安装 http-server)
npx http-server -p 8000

# 访问 http://localhost:8000
```

### 兼容性

| 浏览器 | 版本要求 |
|-------|---------|
| Chrome | ≥ 90 |
| Firefox | ≥ 88 |
| Safari | ≥ 14 |
| Edge | ≥ 90 |

---

## 📄 页面说明

### 主页 (index.html)

- **Hero 区**：大图横幅，展示金泽古镇主题
- **古镇概览**：介绍金泽镇的历史和地理位置
- **古桥遗韵**：6座古桥的卡片式展示，可点击查看详情
- **民俗文化**：介绍金泽庙会和阿婆茶文化

### 古桥详情页（6个）

1. **普济桥**（宋代）：上海第一古桥，咸淳三年建造
2. **万安桥**（宋代）：金泽四十二虹万安为首
3. **迎祥桥**（元代）：连续简支梁桥的鼻祖
4. **如意桥**（元代）：朱元璋与刘伯温的历史故事
5. **天皇阁桥**（明代）：甘宁与要离的墓葬传说
6. **林老桥**（元代）：林青义塾与神医陈莲舫

### 民俗文化页

- **阿婆茶**：上海市非物质文化遗产，介绍历史渊源、民间传说和文化保护计划

---

## 🎨 设计理念

### 色彩系统

```css
--primary-color: #003366;   /* 深水蓝 - 代表江南水乡 */
--secondary-color: #c5a059; /* 古金色 - 代表历史底蕴 */
--text-color: #333;         /* 文字颜色 */
--bg-light: #f4f7f6;        /* 浅色背景 */
```

### 排版规范

- **标题字体**：衬线字体（Georgia / Playfair Display）
- **正文字体**：无衬线字体（Segoe UI / Roboto）
- **行高**：1.6 - 1.8
- **段落间距**：15px - 30px

---

## 🛠️ 开发说明

### 代码规范

- 遵循 W3C HTML5 / CSS3 标准
- 使用语义化 HTML 标签
- CSS 采用 BEM 命名规范
- JavaScript 使用 ES6+ 语法
- 所有注释均为中文

### 响应式断点

```css
/* PC端 */
@media (max-width: 1330px) { /* ... */ }

/* 平板端 */
@media (max-width: 768px) { /* ... */ }

/* 移动端 */
@media (max-width: 480px) { /* ... */ }
```

---

## 📊 性能优化

- ✅ 矢量 SVG Logo，无损缩放
- ✅ 图片懒加载（按需加载）
- ✅ CSS 变量减少重复代码
- ✅ 合理的代码分离（style.css + bridge-detail.css）
- ✅ 纯静态页面，快速加载

---

## 📜 开源协议

本项目采用 [MIT License](LICENSE) 开源协议。

---

## 👤 作者信息

**朱伟杰**

- 学号：212240148
- 学院：上海东海职业技术学院 信息工程学院
- 邮箱：[Petersrsr@outlook.com](mailto:Petersrsr@outlook.com)
- 抖音：[@Petersr](https://www.douyin.com/user/MS4wLjABAAAARfG_9xL9WdIdnGZRyix9I02cZovNJmKY-_o_K9H1ldI?from_tab_name=main)

---

## 🙏 致谢

- 感谢上海青浦金泽镇提供的历史文化资料
- 感谢 [Unsplash](https://unsplash.com) 提供的占位图片
- 感谢开源社区的 CSS Reset 规范

---

## 📝 更新日志

### v1.0.0 (2025-11-21)

- ✨ 初始版本发布
- ✅ 完成主页和 8 个子页面
- ✅ 实现完整的响应式设计
- ✅ 添加汉堡菜单和平滑滚动
- ✅ 优化代码注释和文档

---

<div align="center">

**如果这个项目对你有帮助，请给一个 ⭐️ Star 支持一下！**

Made with ❤️ by Petersr

</div>

