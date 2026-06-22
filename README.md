# さとう土地家屋調査士 行政書士事務所 — デモサイト（パスワード保護）

このリポジトリは [staticrypt](https://github.com/robinmoisson/staticrypt) で
クライアントサイド AES 暗号化した静的サイトです。`index.html` / `sitemap.html`
は暗号化済み（手動編集禁止）。GitHub Pages は `main` ブランチから配信されます。

## 閲覧

`https://enter-web.github.io/satochosasijimusho_demo/` を開き、共有された
パスワードを入力してください。

## 構成

- `index.html` / `sitemap.html` … staticrypt 暗号化済み（CSSはインライン化済み）
- `assets/` … 画像
- `robots.txt` … 検索インデックス回避

## ソース（平文）

平文ソースはこのリポジトリには含まれません。別途バックアップで管理しています。
内容を更新する場合は、平文を再編集 → staticrypt で再暗号化 → 差し替えコミット
してください。
