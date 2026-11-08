# feat: トップページの刷新とリンク追加

Issue: #2

## 方針

- `index.html` を新設する。GitHub Pages（Jekyll）は `index.html` があればそれをトップにし、`README.md` からの自動生成は使わない
- ビルドなしの静的 HTML 1 枚。CSS はインライン、フォントだけ Google Fonts
- ライト / ダーク両対応（`prefers-color-scheme`）、スマホ幅でも崩れないカードグリッド

## セクション

1. Products（receptron）: MulmoCast / MulmoClaude / MulmoTerminal / GraphAI・Grapys
2. Projects: chaff / ever-better / sori / Tax Answer / omochikaeri
3. Singularity Society: 公式サイト / Society's Statement / 開発の心得 / Bootcamp / セキュリティ教育
4. Writing: Zenn / note
5. Tutorials（既存の README の内容）: Codelabs / FriendlyEats / Firebase startup kit

## README

README.md にも同じリンクを追記し、リポジトリ上で見ても内容が揃うようにする。
