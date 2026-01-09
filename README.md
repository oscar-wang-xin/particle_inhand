# 🤖 PARTICLE INHAND

<div align="center">

![3D粒子系统](https://img.shields.io/badge/3D-Particle_System-blue?style=for-the-badge)
![手势识别](https://img.shields.io/badge/Gesture-MediaPipe-green?style=for-the-badge)
![Three.js](https://img.shields.io/badge/3D-Three.js-black?style=for-the-badge)

**基于手势识别的实时3D交互系统**  
*张开手掌扩散粒子，捏合手指聚集粒子*

[🚀 在线演示](#演示) • [📖 使用指南](#使用指南) • [🎯 功能特性](#功能特性)

</div>

---

## ✨ 项目简介

这是一个创新的3D粒子交互系统，结合了先进的计算机视觉技术和3D渲染技术。通过MediaPipe手势识别，用户可以用手势实时控制15,000个粒子的行为，创造出令人惊叹的视觉效果。

### 🎬 演示效果

<div align="center">
  <img src="demo-preview.gif" alt="粒子系统演示" width="600">
  <p><em>实时手势控制粒子动画演示</em></p>
</div>

## 🚀 快速开始

### 环境要求

- **浏览器**: Chrome 88+, Firefox 85+, Safari 14+
- **硬件**: 支持WebGL的现代显卡
- **权限**: 摄像头访问权限 (用于手势识别)
- **网络**: HTTPS或localhost环境

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

### 🎮 使用指南

#### 手势控制
| 手势 | 效果 | 图标 |
|------|------|------|
| 🖐️ 张开手掌 | 粒子扩散 | 🔄 |
| 🤏 捏合手指 | 粒子聚集 | 🎯 |
| 👉 左右移动 | 控制旋转方向 | ↻ |
| ⚡ 快速开合3次 | 触发彩蛋效果 | 🎉 |

#### 鼠标控制
- **左键拖动**: 旋转粒子视角
- **滚轮滚动**: 缩放粒子大小

#### 面板控制
- **模型选择**: 6种粒子形状切换
- **颜色调节**: 实时调整粒子颜色
- **大小调节**: 控制粒子尺寸 (0.01-0.3)

## 🎯 功能特性

### 🌟 核心功能

- **🎨 6种粒子模型**
  - ❤️ 爱心 (心形参数方程)
  - 🪐 土星 (球体+旋转环)
  - 🌸 花朵 (玫瑰线方程)
  - 🎆 烟花 (球形爆炸效果)
  - 🦋 蝴蝶 (蝴蝶曲线)
  - 🔥 火焰 (底部密集扩散)

- **👋 手势识别系统**
  - 实时MediaPipe手势追踪
  - 流畅的粒子响应动画
  - 智能彩蛋触发机制

- **🎮 交互控制**
  - 鼠标拖拽旋转
  - 滚轮缩放控制
  - 实时参数调节

### ⚡ 技术亮点

- **🚀 高性能渲染**: 15,000粒子60fps实时渲染
- **🎨 视觉特效**: 加法混合发光效果
- **🔧 模块化架构**: 清晰的代码组织结构
- **📱 响应式设计**: 自适应不同屏幕尺寸
- **🛡️ 错误处理**: 完善的异常处理机制

## 🛠️ 技术栈

- **前端框架**: 原生HTML5/CSS3/JavaScript (ES6+)
- **3D渲染**: Three.js r128
- **手势识别**: MediaPipe Hands API
- **样式设计**: 科幻风自定义CSS
- **字体**: Orbitron (Google Fonts)

## 📁 项目结构

```
particle-inhand/
├── index.html          # 主入口文件
├── AGENTS.md          # AI助手配置文件 (已忽略)
├── .gitignore         # Git忽略文件
├── LICENSE            # MIT许可证
└── README.md          # 项目说明 (本文档)
```

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

## 🔧 开发与部署

### 开发环境
```bash
# 克隆项目
git clone <repository-url>
cd particle-inhand

# 直接编辑 index.html
# 使用现代浏览器开发工具进行调试
```

### 部署说明
由于是纯前端项目，可直接部署静态文件到任何Web服务器。

## 🤝 贡献指南

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启 Pull Request

## 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情

## 🙏 致谢

- **Three.js**: 强大的3D渲染引擎
- **MediaPipe**: Google的机器学习框架
- **Google Fonts**: 优质字体资源

## 📞 联系方式

- **项目维护者**: Oscar Wang
- **邮箱**: [your-email@example.com]
- **GitHub**: [your-github-profile]

---

<div align="center">

**🎉 享受手势控制3D粒子的奇妙体验吧！**

⭐ 如果这个项目对你有帮助，请给它一个星标！

</div></content>
<parameter name="filePath">README.md