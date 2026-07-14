---
title: Slidev
description: Markdownから作るプレゼンテーションスライド
---

## 概要

Slidev は Markdown から美しいプレゼンテーションスライドを生成するツール。Vue + Vite をベースに、コードハイライト、Mermaid 図表、LaTeX 数式など開発者向けの機能を豊富に備える。1つの `.md` ファイルがそのままスライドになる。

## Markdown / MDX サポート

- Markdown を完全サポート（`---` でスライド区切り）
- MDX は非対応だが、Vue コンポーネントを直接埋め込み可能
- フロントマター（YAML）でレイアウトやテーマを指定
- コードブロックのハイライト、Mermaid、LaTeX に対応

## 主な用途

- テクニカルプレゼンテーション
- カンファレンス登壇資料
- 講義・教材スライド
- ライブコーディングを伴う発表

## 最新バージョン（2026年7月）

| 項目 | 内容 |
|------|------|
| 最新版 | v52.17.0（2026年7月10日） |
| GitHub Stars | 47.6k |
| 初期リリース | 2021年 |
| ライセンス | MIT |

## セットアップ

```bash
# 新規プロジェクト
npm create slidev@latest

# 開発サーバー起動
npm run dev

# エクスポート（PDF）
npm run export
```

## 公式サイト

<https://sli.dev>
