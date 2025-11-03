# TRIZ イノベーター GPT

TRIZの発明原理を使ってアイデアを改良する、親しみやすいカスタムGPTです。

## 📖 概要

このカスタムGPTは、TRIZ（発明的問題解決理論）の専門家として、ユーザーのアイデアや課題を体系的に分析し、創造的な改良案を提案します。初心者でも分かりやすく、実際のアイディエーションを通じてTRIZの考え方を体験できます。

## ✨ できること

- 💡 **新しいアイデアの改良・強化**: 既存のアイデアをTRIZの原理を使ってブラッシュアップ
- 🔧 **製品やサービスの課題解決**: 矛盾やトレードオフを解消する具体的な解決策を提案
- 🎨 **創造的な発想のヒント**: 行き詰まったときの新しい視点を提供
- 🤔 **矛盾する要求の解決**: 技術的・物理的矛盾を特定し、解消方法を提案

## 🎯 こんな人におすすめ

- 製品開発やサービス設計に携わる方
- イノベーションや創造的思考に興味がある方
- TRIZを初めて学ぶ方
- アイデアの壁にぶつかっている方
- 体系的な問題解決手法を学びたい方

## 📚 知識ベース

このGPTは以下の知識ベースを持っています：

- **TRIZ 40の発明原理**: 各原理の詳細な解説と具体例
- **TRIZケーススタディ**: 実際の製品やサービスでの適用事例

## 🚀 使い方

### ChatGPTでの設定方法

1. ChatGPT（ChatGPT Plus/Pro/Team/Enterprise）にログイン
2. 左サイドバーから「Explore GPTs」を選択
3. 右上の「Create」をクリック
4. 「Configure」タブを開く
5. このリポジトリのファイルを以下のように設定：

#### 基本設定
- **Name**: `TRIZ イノベーター`
- **Description**: `TRIZを使ってアイデアを改良する親しみやすいアシスタント`
- **Instructions**: [`instructions.md`](./instructions.md) の内容をコピー&ペースト
- **Conversation starters**: [`conversation-starters.txt`](./conversation-starters.txt) から選択
- **Knowledge**: `knowledge/` フォルダ内のファイルをアップロード
  - `TRIZ_40_Principles_Knowledge_Base.md`
  - `TRIZ_Case_Studies.md`

#### 機能設定
- ✅ **Web Browsing**: ON（最新事例の検索に使用）
- ❌ **DALL·E Image Generation**: OFF
- ❌ **Code Interpreter**: OFF

### 使い方のコツ

1. **まずは自由に話してみる**: 「こんなアイデアを考えているんだけど...」と気軽に話しかけてください
2. **課題を明確にする**: 「〇〇したいけど、△△になってしまう」というジレンマを伝えると効果的
3. **提案された改良案を評価する**: 気に入った案があれば、さらに深掘りをリクエスト
4. **TRIZの学習も兼ねる**: 使われた発明原理を意識することで、自然とTRIZが身につきます

## 📋 リポジトリ構成

```
triz-innovator-gpt/
├── README.md                           # このファイル
├── instructions.md                     # GPTのInstructions（プロンプト）
├── knowledge/                          # 知識ベース
│   ├── TRIZ_40_Principles_Knowledge_Base.md
│   └── TRIZ_Case_Studies.md
├── conversation-starters.txt           # 会話のきっかけ
├── settings.json                       # その他の設定
└── examples/                           # 使用例
    └── sample-sessions.md
```

## 🔗 関連リンク

- [TRIZ公式サイト（英語）](https://www.triz-journal.com/)
- [日本TRIZ協会](http://www.triz-japan.org/)
- ChatGPT カスタムGPTドキュメント

## ⚠️注意

このカスタムGPTを使用するには、ChatGPT Plus、Pro、Team、またはEnterpriseのサブスクリプションが必要です。
