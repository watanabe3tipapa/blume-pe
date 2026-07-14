---
title: Astro
description: コンテンツ駆動のWebフレームワーク
---

## 概要

Astro はコンテンツに特化した Web フレームワーク。**アイランドアーキテクチャ** により、デフォルトでゼロ JavaScript の静的なHTMLを生成し、インタラクティブな部分だけをアイランドとしてクライアントに配信する。

## Markdown / MDX サポート

- `.md` と `.mdx` をネイティブにサポート
- フロントマターによるメタデータ管理
- Content Collections（`src/content/`）による型安全なコンテンツ管理
- Content Layer API による外部CMSとの連携

## 主な用途

- ブログ、ドキュメントサイト、ポートフォリオ
- マーケティングサイト、ランディングページ
- 静的コンテンツ中心のサイト全般

## 最新バージョン（2026年7月）

| 項目 | 内容 |
|------|------|
| 最新安定版 | v6.4（2026年6月リリース） |
| 次世代版 | v7 α（Vite 8 + Rust Compiler 標準搭載） |
| 初期リリース | 2021年 |
| ライセンス | MIT |

## セットアップ

```bash
# 新規プロジェクト
npm create astro@latest

# 開発サーバー起動
npm run dev
```

## 公式サイト

<https://astro.build>
