# GalleyWeb (加密货币资讯与多媒体展示平台)

## 📖 项目简介

本项目（Kyrie's First Dynamic Website）是一个基于 HTML/CSS/JavaScript 构建的响应式前端网站。最初作为《Web应用程序开发》课程的 Project 1 进行开发。网站以加密货币（Cryptocurrency）为主题，详细介绍了比特币的历史与发展，同时集成了多媒体画廊（图片、音频、视频）和博客文章展示功能。

## ✨ 主要特性 (Features)

* **多级下拉导航菜单**：清晰的分类导航，支持访问游戏、体育、动物及加密货币图库，以及音视频专区和博客。
* **动态图片轮播图 (Nivo Slider)**：首页集成了 jQuery Nivo Slider 插件，实现具有平滑过渡效果的宽屏图片轮播。
* **富文本内容排版**：采用经典的“主内容区 + 侧边栏 (Sidebar)”的自适应两栏布局。
* **多媒体集成**：预留了视频 (Video) 和音频 (Audio) 播放的专属页面模块。
* **UI 与图标组件**：全面集成 Font Awesome 4.7.0 图标库，用于呈现精美的社交媒体链接（Twitter, Instagram, YouTube, Facebook）。
* **多主题样式支持**：CSS 架构中包含了 `dark.css`、`light.css`、`default.css` 等不同风格的样式表基座。

## 🛠️ 技术栈 (Tech Stack)

* **前端语言**: HTML5, CSS3
* **脚本逻辑**: JavaScript, jQuery (v1.7.1)
* **第三方插件**:
* [Nivo Slider](https://themeisle.com/plugins/nivo-slider/) (图片轮播)
* [Font Awesome 4.7.0](https://fontawesome.com/v4.7.0/) (矢量图标库)



## 📂 核心目录与文件结构

```text
galleyweb/
├── index.html            # 网站首页（加密货币历史、发展与轮播图）
├── about.html            # 关于我们页面
├── contact.html          # 联系方式页面
├── item1~4.html          # 图库分类展示页面
├── song1~4.html          # 音频展示页面
├── video1~4.html         # 视频展示页面
├── Blog1~4.html          # 博客文章页面
├── css/                  # 样式表目录
│   ├── style.css         # 全局主样式表
│   ├── nivo-slider.css   # 轮播图核心样式
│   └── light/dark/default/ # 轮播图及其他主题样式
├── js/                   # JavaScript 脚本目录
│   ├── jquery-1.7.1.min.js
│   └── jquery.nivo.slider.pack.js
├── images/               # 网站配图、轮播图素材及 Logo
└── font-awesome-4.7.0/   # 本地化的 Font Awesome 字体及样式文件

```

## 🚀 快速开始 (Getting Started)

本项目为纯静态前端项目，无需配置复杂的服务器环境或数据库。

1. 将项目代码克隆或下载到本地。
2. 进入项目根目录。
3. 双击运行 `index.html` 文件，或将其拖拽至任何现代浏览器（Chrome, Firefox, Edge, Safari）中即可预览完整效果。

## 📜 版权与致谢 (Credits)

* **Copyright**: © 2023 Web Application Development (Project 1) -- All Right Reserved.
* 本项目为前端静态网页演示，部分文章内容（如比特币历史）及配图源自互联网开源资料，仅供学术项目展示与学习使用。
