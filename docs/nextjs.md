---
title: Next.js
description: ReactベースのフルスタックWebフレームワーク
---

## 概要

Next.js は Vercel が開発する React ベースのフルスタックフレームワーク。SSR、SSG、ISR、PPR（Partial Prerendering）など多様なレンダリング方式をサポートする。App Router によるファイルベースルーティングが標準。

## Markdown / MDX サポート

- `next-mdx-remote` や `@next/mdx` プラグインで MDX を利用可能
- ファイルベースのルーティングと組み合わせてブログやドキュメントを構築
- 公式の `contentlayer` や community の Content Collections と連携可能

## 主な用途

- 大規模 Web アプリケーション
- ECサイト、SaaS
- SEO 重視のマーケティングサイト
- ドキュメントサイト

## 最新バージョン（2026年7月）

| 項目 | 内容 |
|------|------|
| 最新安定版 | v16.2.4 |
| プレビュー版 | v16.3（Instant Navigations, Turbopack改善） |
| 初期リリース | 2016年 |
| ライセンス | MIT |

## セットアップ

```bash
# 新規プロジェクト
npx create-next-app@latest

# 開発サーバー起動
npm run dev
```

## 公式サイト

<https://nextjs.org>
