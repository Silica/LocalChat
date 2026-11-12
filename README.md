# ChromeのPrompt APIを利用したローカルAIチャットアプリ

Chrome内蔵のGemini NanoをPrompt API経由で利用する、単一HTMLファイルのチャットアプリです。

## Requirements

- PC版Google Chrome
- Prompt API

## 使い方

- index.htmlをChromeで開くだけ
- 会話は端末内で処理され、モデルがダウンロード済みならオフラインでも動作

## 機能

### 画像・音声認識対応

- 音声入力はGPUが必須

### 複数のセッションの切り替え

- サイドバーで会話の作成・切り替え・削除
- 任意のAI応答からの「分岐」で会話を複製
