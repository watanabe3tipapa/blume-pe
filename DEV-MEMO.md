# DEV-MEMO

## プロジェクト概要

- **サイトタイトル**: Markdown-driven Web Frameworks - Trend 2026-07
- **目的**: Markdown (.md) / MDX を利用して構築できるWEBフレームワークを紹介するカタログサイト
- **使用フレームワーク**: Blume (https://useblume.dev)
- **デプロイ先**: GitHub Pages (`https://watanabe3tipapa.github.io/blume-pe/`)
- **ベースパス**: `/blume-pe`
- **更新日**: 2026年7月14日（情報は2026年7月時点）

## 取り上げるフレームワーク

| # | フレームワーク | 最新版 (2026/07) | 言語/基盤 |
|---|---------------|------------------|----------|
| 1 | Astro | v6.4 | JavaScript (Vite) |
| 2 | Next.js | v16.2 | React |
| 3 | Blume | v1.0.3 | Astro + Vite |
| 4 | Gatsby | v5.16 (メンテナンスモード) | React |
| 5 | Docusaurus | v3.10 | React + MDX |
| 6 | VitePress | v1.6 | Vue + Vite |
| 7 | Nuxt | v4.4 | Vue |
| 8 | Remix | v3.0 β (stable: v2.17) | React |
| 9 | Hugo | v0.160 | Go |
| 10 | Jekyll | v4.3 | Ruby |
| 11 | Eleventy (11ty) | v3.1 | JavaScript |
| 12 | Slidev | v52.17 | Vue + Vite |

## サイト構成

```
src/pages/
├── index.md          # トップページ（一覧表 + 概要）
├── astro.md          # Astro
├── nextjs.md         # Next.js
├── blume.md          # Blume（このサイト自身）
├── gatsby.md         # Gatsby
├── docusaurus.md     # Docusaurus
├── vitepress.md      # VitePress
├── nuxt.md           # Nuxt
├── remix.md          # Remix
├── hugo.md           # Hugo
├── jekyll.md         # Jekyll
├── eleventy.md       # Eleventy
└── slidev.md         # Slidev
```

各ページの項目:
- 概要
- Markdown / MDX サポートの特徴
- 主な用途
- 最新バージョン
- セットアップ例
- 公式サイトリンク

## 進捗履歴

- 2026-07-14: プロジェクト初期化、コンテンツ作成、デプロイ設定

## 備考

- Blume 自体も紹介対象として含める（メタ的な構成）
- Gatsby は Netlify 買収後、メンテナンスモードであることを明記
- Jekyll は GitHub Pages 標準だが、新規案件では非推奨の傾向
