---
title: Gatsby
description: Reactベースの静的サイトジェネレーター
---

## 概要

Gatsby は React ベースの静的サイトジェネレーター。GraphQL データレイヤーと豊富なプラグインエコシステムが特徴。2023年に Netlify が買収したが、現在は **メンテナンスモード** に入っており、新規プロジェクトでの採用は推奨されない。

## Markdown / MDX サポート

- `gatsby-source-filesystem` + `gatsby-transformer-remark` で Markdown
- `gatsby-plugin-mdx` で MDX をサポート
- プラグインでヘッドレスCMSと連携可能

## 主な用途

- 既存の Gatsby サイトの維持
- 小〜中規模のブログ・ポートフォリオ
- （新規プロジェクトには非推奨）

## 最新バージョン（2026年7月）

| 項目 | 内容 |
|------|------|
| 最新安定版 | v5.16.0（2026年1月） |
| 状態 | メンテナンスモード（開発実質停止中） |
| 初期リリース | 2015年 |
| ライセンス | MIT |

> **注意**: Netlify 買収後、開発は実質的に停止しています。新規プロジェクトは Astro や Next.js への移行を推奨します。

## セットアップ

```bash
# 新規プロジェクト
npm init gatsby

# 開発サーバー起動
npm run develop
```

## 公式サイト

<https://www.gatsbyjs.com>
