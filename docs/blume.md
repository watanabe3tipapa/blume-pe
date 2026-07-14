---
title: Blume
description: 高速、AI対応、Markdownファーストのドキュメントサイトジェネレーター
---

## 概要

Blume は **Astro と Vite** をベースにしたドキュメントサイトジェネレーター。Markdown のフォルダ構成から自動的にナビゲーションや検索を生成する。ゼロコンフィグで本番品質のドキュメントサイトを数分で構築できる。

**このサイトも Blume で構築されています。**

## Markdown / MDX サポート

- `.md` と `.mdx` を完全サポート
- 30以上のビルトインコンポーネント（Callout, Card, Steps, Tabs, FileTree, CodeGroup, Mermaid など）
- フロントマターによるページタイトル・説明の自動レンダリング
- ディレクティブ構文（`:::note`）でリッチな表現

## 主な用途

- プロダクトのドキュメントサイト
- API リファレンス（OpenAPI / AsyncAPI 対応）
- 開発者向けガイド・チュートリアル
- ブログ、Changelog

## 最新バージョン（2026年7月）

| 項目 | 内容 |
|------|------|
| 最新版 | v1.0.3（2026年7月13日リリース） |
| 初期リリース | 2026年 |
| ライセンス | MIT |
| ベース | Astro + Vite |

## セットアップ

```bash
# 新規プロジェクト
npx blume init

# 開発サーバー起動
npx blume dev

# ビルド
npx blume build
```

## 公式サイト

<https://useblume.dev>
