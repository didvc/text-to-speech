[English](README.md) · 日本語 · [繁體中文](README-zh-TW.md) · [简体中文](README-zh.md) · [Deutsch](README-de.md) · [Français](README-fr.md) · [Español](README-es.md) · [Bahasa Indonesia](README-id.md)

# VoiceFlow - 高機能なテキスト読み上げアプリ

[![Live Demo](https://img.shields.io/badge/Live_Demo-blue?style=for-the-badge)](https://text-speech.pages.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![GitHub issues](https://img.shields.io/github/issues/didvc/text-to-speech?style=for-the-badge)](https://github.com/didvc/text-to-speech/issues)
[![GitHub stars](https://img.shields.io/github/stars/didvc/text-to-speech?style=for-the-badge)](https://github.com/didvc/text-to-speech/stargazers)

React と TypeScript で作られた、多機能でモダンなテキスト読み上げWebアプリです。VoiceFlow は、リアルタイムの単語ハイライト、細かく調整できる音声設定、テキストの管理機能を備え、テキストを自然な音声に変換するための直感的な画面を提供します。

## スクリーンショット

![VoiceFlow のアプリ画面](https://res.cloudinary.com/dxowqxqtj/image/upload/v1753415581/text-to-speech/voiceflow-main-screenshot.png)

*リアルタイムの単語ハイライト、調整できる音声コントロール、テキスト管理を備えた VoiceFlow の直感的な画面。*

## 機能

### 基本機能
- テキスト読み上げ：Web Speech API による高品質な音声合成
- リアルタイムの単語ハイライト：再生中の単語をアニメーションで強調表示
- 再生コントロール：反応のよい再生・一時停止・停止
- 複数の音声に対応：言語の自動判定付きで、システムの音声から選択

### カスタマイズ
- 読み上げ速度の調整：0.5倍から2倍まで
- 音程の調整：聞きやすいように声の高さを微調整
- 音量の調整：出力の大きさを調整
- 音声の選択：システムで使える音声から選択

### テキスト管理
- テキストライブラリ：タイトル付きで複数のテキストを整理
- 追加・編集・削除：テキストの作成、読み込み、更新、削除に完全対応
- テキストの切り替え：複数のテキストをスムーズに切り替え
- 保存：テキストはブラウザにローカル保存

### 画面
- モダンなダークテーマ：目にやさしい洗練されたダーク画面
- レスポンシブデザイン：デスクトップ、タブレット、スマートフォンで快適に動作
- グラデーションのデザイン：美しいグラデーションの文字と装飾
- 直感的な操作：わかりやすい視覚的フィードバック付きの使いやすい画面

## はじめに

### 前提条件
- Node.js（バージョン16以上）
- npm または yarn
- Web Speech API に対応したモダンなブラウザ

### インストール

1. リポジトリをクローンします
   ```bash
   git clone https://github.com/didvc/text-to-speech.git
   cd text-to-speech
   ```

2. 依存関係をインストールします
   ```bash
   npm install
   # or
   yarn install
   ```

3. 開発サーバーを起動します
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. ブラウザを開きます
   `http://localhost:5173` を開くとアプリが表示されます

### 本番用のビルド

```bash
npm run build
# or
yarn build
```

ビルドしたファイルは `dist/` ディレクトリに出力されます。

## 使い方

### 基本的な使い方
1. テキストを選ぶか追加する：用意された例から選ぶか、自分のテキストを追加します
2. 設定を調整する：声、速度、音程、音量を好みに合わせます
3. 再生する：再生ボタンを押して読み上げを始めます
4. 目で追う：読まれている単語がリアルタイムでハイライトされます

### 高度な機能
- テキスト管理：ライブラリで複数の文書を整理
- 音声の切り替え：さまざまな声や言語を試せます
- 速度の調整：理解のしやすさやアクセシビリティに合わせて読む速さを調整
- スマートフォン対応：すべての機能をモバイルでも利用可能

## 技術スタック

- フロントエンドフレームワーク：React 18
- 言語：TypeScript
- ビルドツール：Vite
- スタイリング：Tailwind CSS
- アイコン：Lucide React
- 音声API：Web Speech API（SpeechSynthesis）

## 対応ブラウザ

VoiceFlow は Web Speech API に対応したモダンなブラウザで動作します:

- Chrome/Chromium（推奨）
- Edge
- Safari
- Firefox（選べる音声は限られます）
- モバイルブラウザ（iOS Safari、Chrome Mobile）

## レスポンシブデザイン

VoiceFlow はあらゆる種類の端末でスムーズに動くように作られています:
- デスクトップ：最適化されたレイアウトですべての機能
- タブレット：タッチしやすい画面と適応するコントロール
- スマートフォン：主要な機能にアクセスしやすいコンパクトな画面

## コントリビュート

コミュニティからのコントリビューションを歓迎します！始め方の詳細は[コントリビューションガイド](CONTRIBUTING.md)を参照してください。

### コントリビューターのためのクイックスタート
1. リポジトリをフォークします
2. フィーチャーブランチを作成します（`git checkout -b feature/amazing-feature`）
3. 変更を加えます
4. 変更をコミットします（`git commit -m 'Add amazing feature'`）
5. ブランチをプッシュします（`git push origin feature/amazing-feature`）
6. プルリクエストを作成します

## ライセンス

このプロジェクトは MIT ライセンスで公開しています。詳しくは [LICENSE](LICENSE) ファイルを参照してください。

## 問題報告とサポート

- バグ報告：[Issue を作成](https://github.com/didvc/text-to-speech/issues/new?template=bug_report.yml)
- 機能要望：[機能をリクエスト](https://github.com/didvc/text-to-speech/issues/new?template=feature_request.yml)
- ディスカッション：[会話に参加](https://github.com/didvc/text-to-speech/discussions)

## 謝辞

- テキスト読み上げ機能を提供する Web Speech API
- すばらしいツールを提供する React と TypeScript のコミュニティ
- 美しいスタイリングを支える Tailwind CSS
- すっきりとしたモダンなアイコンの Lucide React

## プロジェクトの特徴

- ビルドサイズ：高速な読み込みのために最適化
- 依存関係：最小限で、慎重に選定
- パフォーマンス：なめらかな60fpsのアニメーションと素早い反応
- アクセシビリティ：キーボード操作に対応し、WCAG に準拠

---

<div align="center">

[VoiceFlow を試す](https://text-speech.pages.dev) | [ドキュメント](https://github.com/didvc/text-to-speech/wiki) | [ディスカッション](https://github.com/didvc/text-to-speech/discussions)

作成：[didvc](https://github.com/didvc)

</div>