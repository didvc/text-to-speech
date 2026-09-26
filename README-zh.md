[English](README.md) · [日本語](README-ja.md) · [繁體中文](README-zh-TW.md) · 简体中文 · [Deutsch](README-de.md) · [Français](README-fr.md) · [Español](README-es.md) · [Bahasa Indonesia](README-id.md)

# VoiceFlow - 高级文本转语音应用

[![Live Demo](https://img.shields.io/badge/Live_Demo-blue?style=for-the-badge)](https://text-speech.pages.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![GitHub issues](https://img.shields.io/github/issues/didvc/text-to-speech?style=for-the-badge)](https://github.com/didvc/text-to-speech/issues)
[![GitHub stars](https://img.shields.io/github/stars/didvc/text-to-speech?style=for-the-badge)](https://github.com/didvc/text-to-speech/stargazers)

一个用 React 和 TypeScript 构建、功能丰富的现代文本转语音网页应用。VoiceFlow 提供直观的界面，把文本转换为自然的语音，并支持实时单词高亮、可自定义的语音设置和内容管理功能。

## 截图

![VoiceFlow 应用界面](https://res.cloudinary.com/dxowqxqtj/image/upload/v1753415581/text-to-speech/voiceflow-main-screenshot.png)

*VoiceFlow 的直观界面，具备实时单词高亮、可自定义的语音控制和内容管理。*

## 功能

### 核心功能
- 文本转语音：使用 Web Speech API 进行高质量语音合成
- 实时单词高亮：播放时用动画高亮单词，提供视觉反馈
- 播放控制：响应灵敏的播放、暂停和停止
- 多种语音：可从系统语音中选择，并自动检测语言

### 自定义
- 可调语速：播放速度可在 0.5 倍到 2 倍之间调节
- 音调控制：微调声音高低，获得最佳收听体验
- 音量控制：调节输出音量
- 语音选择：从系统可用的语音中选择

### 内容管理
- 文本库：用标题整理多份文本文档
- 添加/编辑/删除：完整的文本内容增删改查
- 内容切换：在不同文本之间无缝切换
- 持久存储：内容保存在浏览器本地

### 用户界面
- 现代深色主题：简洁护眼的深色界面
- 响应式设计：在桌面、平板和手机上都运行良好
- 渐变品牌风格：漂亮的渐变文字和视觉元素
- 直观操作：有清晰视觉反馈、易于上手的界面

## 开始使用

### 前提条件
- Node.js（16 或更高版本）
- npm 或 yarn 包管理器
- 支持 Web Speech API 的现代浏览器

### 安装

1. 克隆仓库
   ```bash
   git clone https://github.com/didvc/text-to-speech.git
   cd text-to-speech
   ```

2. 安装依赖
   ```bash
   npm install
   # or
   yarn install
   ```

3. 启动开发服务器
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. 打开浏览器
   访问 `http://localhost:5173` 即可看到应用

### 生产构建

```bash
npm run build
# or
yarn build
```

构建后的文件会输出到 `dist/` 目录。

## 使用方法

### 基本用法
1. 选择或添加文本：从预置的示例中选择，或添加你自己的文本内容
2. 调整设置：按喜好调整语音、速度、音调和音量
3. 播放：点击播放按钮开始文本转语音
4. 跟读：朗读时观看实时的单词高亮

### 高级功能
- 内容管理：用文本库整理多份文档
- 切换语音：尝试不同的语音和语言
- 速度控制：为理解或无障碍需求调整朗读速度
- 移动端支持：在移动设备上也能使用全部功能

## 技术栈

- 前端框架：React 18
- 语言：TypeScript
- 构建工具：Vite
- 样式：Tailwind CSS
- 图标：Lucide React
- 语音 API：Web Speech API（SpeechSynthesis）

## 浏览器兼容性

VoiceFlow 可在支持 Web Speech API 的现代浏览器上运行：

- Chrome/Chromium（推荐）
- Edge
- Safari
- Firefox（可选语音较少）
- 移动浏览器（iOS Safari、Chrome Mobile）

## 响应式设计

VoiceFlow 设计为可在各类设备上流畅运行：
- 桌面：完整功能和优化布局
- 平板：适合触控的界面和自适应控件
- 手机：紧凑设计，主要功能都方便使用

## 贡献

欢迎社区贡献！如何开始的详细说明请参阅[贡献指南](CONTRIBUTING.md)。

### 贡献者快速入门
1. Fork 仓库
2. 创建功能分支（`git checkout -b feature/amazing-feature`）
3. 进行修改
4. 提交改动（`git commit -m 'Add amazing feature'`）
5. 推送分支（`git push origin feature/amazing-feature`）
6. 发起 Pull Request

## 许可证

本项目采用 MIT 许可证，详情请参阅 [LICENSE](LICENSE) 文件。

## 问题与支持

- 错误报告：[创建 issue](https://github.com/didvc/text-to-speech/issues/new?template=bug_report.yml)
- 功能请求：[提出功能请求](https://github.com/didvc/text-to-speech/issues/new?template=feature_request.yml)
- 讨论：[加入讨论](https://github.com/didvc/text-to-speech/discussions)

## 致谢

- 提供文本转语音功能的 Web Speech API
- 提供出色工具的 React 和 TypeScript 社区
- 提供漂亮样式系统的 Tailwind CSS
- 提供简洁现代图标的 Lucide React

## 项目特点

- 构建体积：为快速加载而优化
- 依赖：精简且经过仔细挑选
- 性能：流畅的 60fps 动画和灵敏的交互
- 无障碍：支持键盘导航，符合 WCAG

---

<div align="center">

[立即试用 VoiceFlow](https://text-speech.pages.dev) | [文档](https://github.com/didvc/text-to-speech/wiki) | [讨论](https://github.com/didvc/text-to-speech/discussions)

制作：[didvc](https://github.com/didvc)

</div>