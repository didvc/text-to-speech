[English](README.md) · [日本語](README-ja.md) · 繁體中文 · [简体中文](README-zh.md) · [Deutsch](README-de.md) · [Français](README-fr.md) · [Español](README-es.md) · [Bahasa Indonesia](README-id.md)

# VoiceFlow - 進階文字轉語音應用程式

[![Live Demo](https://img.shields.io/badge/Live_Demo-blue?style=for-the-badge)](https://text-speech.pages.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![GitHub issues](https://img.shields.io/github/issues/didvc/text-to-speech?style=for-the-badge)](https://github.com/didvc/text-to-speech/issues)
[![GitHub stars](https://img.shields.io/github/stars/didvc/text-to-speech?style=for-the-badge)](https://github.com/didvc/text-to-speech/stargazers)

一個以 React 與 TypeScript 打造、功能豐富的現代文字轉語音網頁應用程式。VoiceFlow 提供直覺的介面，將文字轉換為自然的語音，並具備即時單字醒目提示、可自訂的語音設定，以及內容管理功能。

## 螢幕截圖

![VoiceFlow 應用程式介面](https://res.cloudinary.com/dxowqxqtj/image/upload/v1753415581/text-to-speech/voiceflow-main-screenshot.png)

*VoiceFlow 的直覺介面，具備即時單字醒目提示、可自訂的語音控制與內容管理。*

## 功能

### 核心功能
- 文字轉語音：使用 Web Speech API 進行高品質語音合成
- 即時單字醒目提示：播放時以動畫醒目提示單字，提供視覺回饋
- 播放控制：反應靈敏的播放、暫停與停止
- 多種語音：可從系統提供的語音中選擇，並自動偵測語言

### 自訂
- 可調整語速：播放速度可從 0.5 倍調到 2 倍
- 音高控制：微調聲音高低，獲得最佳聆聽體驗
- 音量控制：調整輸出音量
- 語音選擇：從系統可用的語音中選擇

### 內容管理
- 文字庫：以標題整理多份文字文件
- 新增／編輯／刪除：完整的文字內容增刪改查操作
- 內容切換：在不同文字之間順暢切換
- 持久儲存：內容保存在瀏覽器本機

### 使用者介面
- 現代深色主題：俐落又護眼的深色介面
- 響應式設計：在桌機、平板與手機上都運作良好
- 漸層品牌風格：美麗的漸層文字與視覺元素
- 直覺操作：清楚視覺回饋、容易上手的介面

## 開始使用

### 先決條件
- Node.js（16 版以上）
- npm 或 yarn 套件管理工具
- 支援 Web Speech API 的現代瀏覽器

### 安裝

1. Clone 儲存庫
   ```bash
   git clone https://github.com/didvc/text-to-speech.git
   cd text-to-speech
   ```

2. 安裝相依套件
   ```bash
   npm install
   # or
   yarn install
   ```

3. 啟動開發伺服器
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. 開啟瀏覽器
   前往 `http://localhost:5173` 即可看到應用程式

### 建置正式版本

```bash
npm run build
# or
yarn build
```

建置後的檔案會輸出到 `dist/` 目錄。

## 使用方式

### 基本用法
1. 選擇或新增文字：從預先載入的範例中選擇，或加入自己的文字內容
2. 調整設定：依喜好調整語音、速度、音高與音量
3. 播放：按下播放按鈕開始文字轉語音
4. 跟著閱讀：朗讀時觀看即時的單字醒目提示

### 進階功能
- 內容管理：用文字庫整理多份文件
- 切換語音：嘗試不同的語音與語言
- 速度控制：為了理解或無障礙需求調整朗讀速度
- 行動裝置支援：在行動裝置上也能使用完整功能

## 技術堆疊

- 前端框架：React 18
- 語言：TypeScript
- 建置工具：Vite
- 樣式：Tailwind CSS
- 圖示：Lucide React
- 語音 API：Web Speech API（SpeechSynthesis）

## 瀏覽器相容性

VoiceFlow 可在支援 Web Speech API 的現代瀏覽器上運作：

- Chrome/Chromium（建議）
- Edge
- Safari
- Firefox（可選語音較少）
- 行動瀏覽器（iOS Safari、Chrome Mobile）

## 響應式設計

VoiceFlow 設計為能在各種裝置上順暢運作：
- 桌機：完整功能與最佳化版面
- 平板：適合觸控的介面與自適應控制
- 手機：精簡設計，主要功能都方便使用

## 貢獻

歡迎社群貢獻！如何開始的詳細說明請參閱[貢獻指南](CONTRIBUTING.md)。

### 貢獻者快速入門
1. Fork 儲存庫
2. 建立功能分支（`git checkout -b feature/amazing-feature`）
3. 進行修改
4. 提交變更（`git commit -m 'Add amazing feature'`）
5. 推送分支（`git push origin feature/amazing-feature`）
6. 開啟 Pull Request

## 授權

本專案採用 MIT 授權，詳情請參閱 [LICENSE](LICENSE) 檔案。

## 問題與支援

- 錯誤回報：[建立 issue](https://github.com/didvc/text-to-speech/issues/new?template=bug_report.yml)
- 功能請求：[提出功能請求](https://github.com/didvc/text-to-speech/issues/new?template=feature_request.yml)
- 討論：[加入討論](https://github.com/didvc/text-to-speech/discussions)

## 致謝

- 提供文字轉語音功能的 Web Speech API
- 提供優秀工具的 React 與 TypeScript 社群
- 提供美麗樣式系統的 Tailwind CSS
- 提供簡潔現代圖示的 Lucide React

## 專案特色

- 建置大小：為快速載入最佳化
- 相依套件：精簡且經過審慎挑選
- 效能：流暢的 60fps 動畫與靈敏的互動
- 無障礙：支援鍵盤操作，符合 WCAG

---

<div align="center">

[立即試用 VoiceFlow](https://text-speech.pages.dev) | [文件](https://github.com/didvc/text-to-speech/wiki) | [討論](https://github.com/didvc/text-to-speech/discussions)

製作：[didvc](https://github.com/didvc)

</div>