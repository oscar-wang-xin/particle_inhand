# 🤖 PARTICLE INHAND

<div align="center">

**基于手势识别的实时3D粒子交互系统**  
*Open your palm to spread particles, pinch fingers to gather particles*

[![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) 
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6%2B-yellow)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) 
[![Three.js](https://img.shields.io/badge/Three.js-r128-blue)](https://threejs.org/) 
[![MediaPipe](https://img.shields.io/badge/MediaPipe-Hands-green)](https://mediapipe.dev/solutions/hands)

🇺🇸 [English](README-en.md) • 🇨🇳 [简体中文](README.md)

<br>

[🚀 快速开始](#快速开始) • [📖 使用指南](#使用指南) • [🎯 功能特性](#功能特性) • [🛠️ 技术栈](#技术栈) • [🎨 视觉设计](#视觉设计)

</div>

---

## ✨ 项目简介

**Particle Inhand** 是一个创新的3D粒子交互系统，结合了先进的计算机视觉技术和3D渲染技术。通过MediaPipe手势识别，用户可以用手势实时控制15,000个粒子的行为，创造出令人惊叹的视觉效果。

该项目展示了如何将人工智能手势识别技术与3D图形渲染技术相结合，创造出沉浸式的用户交互体验。

---

## 🎬 截图展示

<div align="center">

### 🖥️ 主界面
![粒子系统主界面](screenshot/2026-01-09_2135004.png)
<em>主界面显示粒子控制面板和手势识别状态</em>

### ✨ 粒子动画效果
![粒子动画效果](screenshot/2026-01-09_2134002.png)
<em>实时粒子动画与手势控制效果</em>

</div>

---

## 🚀 快速开始

### 环境要求

| 要求 | 说明 |
|------|------|
| **浏览器** | Chrome 88+, Firefox 85+, Safari 14+ |
| **硬件** | 支持WebGL的现代显卡 |
| **权限** | 摄像头访问权限 (用于手势识别) |
| **网络** | HTTPS或localhost环境 |

### 运行项目

```bash
# 方式1: 直接在浏览器中打开
# 双击 index.html 或拖拽到浏览器窗口

# 方式2: 使用本地服务器 (推荐)
# Python 3
python -m http.server 8000

# Node.js (需要安装 http-server)
npx http-server

# 然后在浏览器中访问 http://localhost:8000
```

---

## 🎮 使用指南

### 手势控制

| 手势 | 效果 | 图标 |
|------|------|------|
| 🖐️ 张开手掌 | 粒子扩散 | 🔄 |
| 🤏 捏合手指 | 粒子聚集 | 🎯 |
| 👉 左右移动 | 控制旋转方向 | ↻ |
| ⚡ 快速开合3次 | 触发彩蛋效果 | 🎉 |

### 鼠标控制

- **左键拖动**: 旋转粒子视角
- **滚轮滚动**: 缩放粒子大小

### 面板控制

- **模型选择**: 切换6种粒子形状
- **颜色调节**: 实时调整粒子颜色
- **大小调节**: 控制粒子尺寸 (0.01-0.3)

---

##  功能特性

### ✨ 核心特性

- ✋ **手势控制** - 实时MediaPipe手势追踪，粒子随手势动态响应
- 🎨 **6种粒子模型** - 爱心、土星、花朵、烟花、蝴蝶、火焰
- 🚀 **高性能渲染** - 60fps流畅运行15,000个粒子
- 🌟 **科幻视觉效果** - 未来感UI设计，炫酷光影特效
- 🎮 **多模式控制** - 支持手势、鼠标和面板控制

### 📦 粒子模型

| 模型 | 描述 |
|------|------|
| ❤️ 爱心 | 心形参数方程 |
| 🪐 土星 | 球体+旋转环 |
| 🌸 花朵 | 玫瑰线方程 |
| 🎆 烟花 | 球形爆炸效果 |
| 🦋 蝴蝶 | 蝴蝶曲线 |
| 🔥 火焰 | 底部密集扩散 |

### ⚡ 技术亮点

- **实时手势识别**: 基于MediaPipe的高性能手势追踪
- **流畅动画效果**: 60fps渲染15,000个粒子
- **模块化架构**: 清晰的代码组织结构，易于扩展
- **响应式设计**: 自适应不同屏幕尺寸
- **丰富交互体验**: 支持多种控制方式和彩蛋效果

---

## 🛠️ 技术栈

| 类别 | 技术 | 用途 |
|------|------|------|
| **前端开发** | HTML5/CSS3 | 页面结构和样式 |
| **编程语言** | JavaScript (ES6+) | 交互逻辑和业务实现 |
| **3D渲染** | Three.js r128 | 高性能3D图形渲染 |
| **计算机视觉** | MediaPipe Hands API | 实时手势识别 |
| **样式设计** | 自定义CSS | 科幻主题UI设计 |
| **字体** | Orbitron (Google Fonts) | 科技感字体 |

---

## 🎨 视觉设计

### 科幻主题

- **色彩方案**: 青色(#00FFFF)科技感配色
- **背景效果**: 三维宇宙网格 + 动态光晕
- **动画效果**: 流畅的粒子过渡动画
- **UI设计**: 未来感控制面板

### 性能优化

- **LOD系统**: 距离剔除优化
- **内存管理**: 高效对象生命周期
- **渲染优化**: 节流和防抖技术

---

## 🔧 开发与部署

### 开发环境

1. **克隆项目**
   ```bash
   git clone https://github.com/oscarwang164/particle-inhand.git
   cd particle-inhand
   ```

2. **开发方式**
   - 直接编辑 `index.html` 文件
   - 使用现代浏览器开发工具进行调试
   - 无需构建工具，修改后即可在浏览器中查看效果

### 部署说明

该项目是纯前端项目，无需后端服务，可通过以下方式部署：

1. **本地部署**：
   ```bash
   # 使用Python启动本地服务器
   python -m http.server 8000
   
   # 或使用Node.js
   npx http-server
   ```

2. **生产部署**：
   - 上传所有静态文件到任何Web服务器
   - 支持GitHub Pages、Vercel、Netlify等静态网站托管服务
   - 确保服务器支持HTTPS（摄像头访问需要安全连接）

---

## 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情

---

## 🙏 致谢

- [Three.js](https://threejs.org/) - 强大的3D渲染引擎
- [MediaPipe](https://mediapipe.dev/) - Google的机器学习框架
- [Google Fonts](https://fonts.google.com/) - 优质字体资源

---

## 📞 联系方式

- **项目维护者**: Oscar Wang
- **邮箱**: [164938@qq.com](mailto:164938@qq.com)
- **GitHub**: [@oscarwang164](https://github.com/oscarwang164)

---

## 🤝 贡献指南

欢迎对本项目进行贡献！无论是提交bug报告、提出新功能建议，还是直接提交代码，我们都非常欢迎。

### 如何贡献

1. **提交Issue**: 如果您发现了bug或有新的功能建议，请在GitHub上提交Issue
2. **Fork项目**: 点击右上角的"Fork"按钮，将项目Fork到您的GitHub账号
3. **创建分支**: 在您的Fork中创建一个新的分支来开发新功能或修复bug
4. **提交PR**: 完成开发后，提交Pull Request到主分支

### 贡献规范

- 保持代码风格一致
- 为新功能添加必要的注释
- 确保所有修改都经过测试
- 提交PR时请清晰描述修改内容

---

## 📊 项目状态

- **当前版本**: 1.0.0
- **开发状态**: 维护中
- **最后更新**: 2026-01-09

---

<div align="center">

**🎉 享受手势控制3D粒子的奇妙体验吧！**

⭐ 如果这个项目对你有帮助，请给它一个星标！

</div>