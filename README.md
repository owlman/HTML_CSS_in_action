# HTML5+CSS3 网页设计项目教材

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/zh-CN/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/zh-CN/docs/Web/CSS)
[![Bootstrap 5](https://img.shields.io/badge/Bootstrap_5-7952B3?style=flat&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
[![FontAwesome 5](https://img.shields.io/badge/FontAwesome_5-528DD7?style=flat&logo=fontawesome&logoColor=white)](https://fontawesome.com/)
[![NPM](https://img.shields.io/badge/NPM-CB3837?style=flat&logo=npm&logoColor=white)](https://www.npmjs.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

一本面向前端初学者的网页设计教材，通过 5 个企业级项目实践，循序渐进地教授 HTML5 + CSS3 + Bootstrap 网页设计技术。

## 📖 内容概要

本书基于"凌雪冰熊"连锁饮料店的企业网站开发案例，设计了 5 个由浅入深的网页设计项目：

| 项目 | 章节 | 内容 | 核心技术 |
|------|------|------|----------|
| 1 | 第 1 章 | 企业的线上名片设计 | HTML 基础、CSS 基础、FontAwesome 图标库 |
| 2 | 第 2 章 | 企业网站的首页设计 | HTML5 布局标签、Bootstrap 网格系统、响应式设计 |
| 3 | 第 3 章 | 企业网站的新闻活动页设计 | 图文排版、CSS 配色方案 |
| 4 | 第 4 章 | 企业网站的产品展示页设计 | 多媒体播放、Flexbox 布局 |
| 5 | 第 5 章 | 企业网站的申请表单页设计 | 表单设计、用户界面交互 |

## 🎯 特色

- **项目驱动**：每个知识点都对应一个真实的企业需求，而非孤立讲解
- **授之以渔**：侧重培养快速学习任意网页设计框架的能力，而非局限于某一框架
- **纯前端**：全书不涉及 JavaScript、Python 等编程语言，专注 HTML + CSS
- **全程手写代码**：所有代码都手动输入，而非依赖可视化工具或 AI 生成
- **配套源码**：每个项目都有完整的、可运行的示例代码

## 📂 项目结构

```bash
├── Markdown/             # 书稿内容（Markdown 格式）
│   ├── 00.md             # 前言
│   ├── 01.md             # 项目 1：企业的线上名片设计
│   ├── 02.md             # 项目 2：企业网站的首页设计
│   ├── 03.md             # 项目 3：企业网站的新闻活动页设计
│   ├── 04.md             # 项目 4：企业网站的产品展示页设计
│   └── 05.md             # 项目 5：企业网站的申请表单页设计
│
├── Examples/             # 示例代码
│   ├── 00_demo/          # Bootstrap 框架演示
│   ├── 01_BusinessCard/  # 项目 1 代码：线上名片
│   └── 02_SnowBear/      # 项目 2-5 代码：凌雪冰熊企业网站
│
├── LICENSE               # MIT 开源协议
├── README.md             # 项目说明
└── .gitignore            # Git 忽略配置
```

## 🚀 快速开始

### 环境准备

- **代码编辑器**：VS Code（推荐）、WebStorm 或 Visual Studio
- **浏览器**：Google Chrome、Mozilla Firefox 或 Microsoft Edge
- **版本控制**：Git（可选，但推荐）

### 运行示例

1. 克隆本仓库：

    ```bash
    git clone git@github.com:owlman/HTML_CSS_in_action.git
    cd ./Examples/01_BusinessCard
    ```

2. 使用 VS Code 打开项目，或直接双击 `index.htm` 在浏览器中预览

3. 如需使用 Bootstrap 框架：

    ```bash
    cd Examples/02_SnowBear
    npm install
    ```

## 📚 适合读者

- 前端开发初学者
- 希望系统学习 HTML + CSS 的后端开发者
- 培训机构的学员和教师
- 需要补充网页设计基础知识的程序员

## ⚠️ 前提知识

本书不要求读者有任何编程经验，但建议具备：

- 基本的计算机操作能力
- 能够使用文本编辑器
- 了解浏览器的基本使用方法

## 🔧 技术栈

- **标记语言**：HTML5
- **样式语言**：CSS3
- **框架**：Bootstrap 5.x
- **图标库**：FontAwesome 5.x
- **构建工具**：npm（仅用于管理 Bootstrap 依赖）

## 📄 开源协议

本项目基于 [MIT License](LICENSE) 开源，您可以：

- ✅ 自由使用、修改、分发本项目
- ✅ 将本项目用于商业或非商业目的
- ✅ 为本项目贡献代码或提交问题反馈

唯一要求是保留原作者的版权声明。

## 🙏 致谢

- [Bootstrap 框架](https://getbootstrap.com/) - Twitter 公司开源的前端框架
- [FontAwesome](https://fontawesome.com/) - 优秀的图标库
- [VS Code](https://code.visualstudio.com/) - 微软开源的代码编辑器

---

如果您觉得这个项目对您有帮助，欢迎 star ⭐ 或分享给需要的朋友！
