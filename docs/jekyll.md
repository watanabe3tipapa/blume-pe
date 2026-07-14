---
title: Jekyll
description: Ruby製の静的サイトジェネレーター、GitHub Pages標準
---

## 概要

Jekyll は Ruby で書かれた静的サイトジェネレーター。GitHub Pages の標準エンジンとして広く使われてきた。Liquid テンプレートエンジンと Markdown を組み合わせてシンプルなブログやサイトを構築できる。2026年現在、新規プロジェクトでは Astro や Hugo が推奨される。

## Markdown / MDX サポート

- Markdown（Kramdown）を完全サポート
- MDX は非対応
- Liquid テンプレートによる動的コンテンツ生成
- フロントマター（YAML）による設定

## 主な用途

- GitHub Pages でのブログ・ポートフォリオ
- 個人ブログ（小規模）
- 既存の Jekyll サイトの維持

## 最新バージョン（2026年7月）

| 項目 | 内容 |
|------|------|
| 最新版 | v4.3.x（GitHub Pages は v3.9 固定） |
| GitHub Stars | 49.2k |
| 初期リリース | 2008年 |
| ライセンス | MIT |

> **注意**: Jekyll は静的サイトジェネレーターの草分けですが、2026年はメンテナンスフェーズです。新規プロジェクトには Eleventy、Hugo、Astro を推奨します。

## セットアップ

```bash
# 新規プロジェクト
gem install jekyll bundler
jekyll new my-site
cd my-site

# 開発サーバー起動
bundle exec jekyll serve
```

## 公式サイト

<https://jekyllrb.com>
