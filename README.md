# AI Vibe Coding

> **用 AI 辅助编程，把灵感快速做成可运行、可展示、可分享的小作品。**

个人学习与作品展示仓库：收录我在 Vibe Coding 过程中完成的交互 demo、视觉实验和创意原型。每个子项目尽量保持**单文件或极简依赖**，方便克隆、本地打开、部署到 GitHub Pages，也适合作为面试与开源作品集的一部分。

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

---

## 为什么做这个仓库

- **学习**：记录从想法到可运行原型的完整路径（WebGL、摄像头、手势、Shader 等）
- **展示**：给招聘方、合作方一个可点击、可体验的入口
- **开源**：欢迎 Star / Fork / Issue，一起改进创意与技术实现

---

## 项目列表

| 项目 | 说明 | 体验方式 |
|------|------|----------|
| [liquid-touch-camera](./projects/liquid-touch-camera/) | 实时摄像头 + 水面物理模拟 + 触摸/手势扰动，LIQUID / CRYSTAL 双模式 | 本地打开 `index.html`，或部署后通过 HTTPS 访问（需摄像头权限） |

> 新项目会陆续放在 [`projects/`](./projects/) 目录下，每个子文件夹自带说明。

---

## 快速开始

```bash
git clone https://github.com/NickWilde-AI/AI-Vibe-Coding-.git
cd AI-Vibe-Coding-

# 示例：在浏览器中打开 Liquid Touch Camera
open projects/liquid-touch-camera/index.html
```

**注意**：涉及摄像头的页面需在 **HTTPS** 或 `localhost` 下运行；直接双击打开部分浏览器可能限制 `getUserMedia`。

### GitHub Pages（可选）

将仓库 Settings → Pages → Source 设为 `main` 分支 `/root` 或指定 `docs/`，即可通过 Pages URL 在线体验（具体路径取决于你如何组织静态资源）。

---

## 技术栈（随项目变化）

当前首个 demo 主要使用：

- WebGL 1.0（自定义水面模拟与折射渲染）
- MediaPipe Hands（手势追踪，CDN 加载）
- 原生 HTML / CSS / JavaScript，无构建步骤

---

## 参与与反馈

- 觉得某个 demo 有趣：**Star** 一下是对我最大的鼓励
- 发现问题或有改进想法：欢迎提 **Issue** 或 **PR**
- 商业合作 / 面试交流：可通过 GitHub Profile 联系我

---

## License

本项目默认采用 [MIT License](./LICENSE)，除非某个子项目目录内另有说明。
