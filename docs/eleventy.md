---
title: Eleventy (11ty)
description: シンプルで柔軟なJavaScript製静的サイトジェネレーター
---

## 概要

Eleventy（11ty）は JavaScript ベースの静的サイトジェネレーター。複数のテンプレートエンジン（Liquid、Nunjucks、Handlebars など）をサポートし、設定不要で動作するシンプルさが特徴。クライアントに JavaScript を一切配信しないゼロJSビルドが可能。

## Markdown / MDX サポート

- Markdown を標準サポート（`markdown-it` パーサー）
- MDX はプラグインで対応可能
- フロントマター（YAML/JSON/TOML）
- 複数テンプレートエンジンとの組み合わせが可能

## 主な用途

- シンプルなブログ・ポートフォリオ
- ドキュメントサイト
- プロトタイプ・個人サイト
- 最小構成のサイト

## 最新バージョン（2026年7月）

| 項目 | 内容 |
|------|------|
| 最新安定版 | v3.1.6（2026年6月2日） |
| 次世代版 | v4.0.0-alpha.10（開発中 / Build Awesome へ名称変更予定） |
| 初期リリース | 2017年 |
| ライセンス | MIT |

## セットアップ

```bash
# 新規プロジェクト
npm init -y
npm install @11ty/eleventy

# 開発サーバー起動
npx @11ty/eleventy --serve
```

## 公式サイト

<https://www.11ty.dev>
