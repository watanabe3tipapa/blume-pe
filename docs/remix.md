---
title: Remix
description: Web標準に基づくReactフレームワーク
---

## 概要

Remix は Web 標準（Fetch API、FormData）に基づく React フレームワーク。プログレッシブエンハンスメントを重視し、JavaScript がなくても動作するフォームやナビゲーションを提供する。2024年に React Router と統合された。

## Markdown / MDX サポート

- MDX の公式サポートあり（`@remix-run/mdx` または React Router v7 の MDX ルート）
- route モジュールの `loader` と組み合わせてデータ駆動の MDX ページを構築
- フロントマターのパースは別途設定が必要

## 主な用途

- データ駆動型 Web アプリケーション
- 管理画面・ダッシュボード
- フォーム中心のサイト（EC、予約など）

## 最新バージョン（2026年7月）

| 項目 | 内容 |
|------|------|
| 最新安定版 | v2.17.4 |
| 次世代版 | v3.0.0-beta.5（React Router v7 ベース） |
| 初期リリース | 2021年 |
| ライセンス | MIT |

## セットアップ

```bash
# 新規プロジェクト（v3 β）
npx create-remix@latest

# 開発サーバー起動
npm run dev
```

## 公式サイト

<https://remix.run>
