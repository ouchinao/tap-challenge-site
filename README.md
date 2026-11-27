# tap-challenge-site

iPhone アプリ「連打チャレンジ（Tap Challenge）」のサポートとプライバシーポリシーのページです。
GitHub Pages（ブランチ `main`）で公開します。

| ページ | 日本語 | English |
|---|---|---|
| サポート | [/support](https://ouchinao.github.io/tap-challenge-site/support) | [/en/support](https://ouchinao.github.io/tap-challenge-site/en/support) |
| プライバシーポリシー | [/privacy](https://ouchinao.github.io/tap-challenge-site/privacy) | [/en/privacy](https://ouchinao.github.io/tap-challenge-site/en/privacy) |

## 直し方

- **サポート**（`support.md`、`en/support.md`）は、このリポジトリで直します
- **プライバシーポリシー**（`privacy.md`、`en/privacy.md`）は、ここでは直しません。アプリに同梱した文面
  （アプリのリポジトリの `assets/privacy/*.md`）を直し、アプリのリポジトリで
  `python3 tool/export_site_pages.py <このリポジトリのフォルダ>` を実行して書き出します。
  ここで直すと、アプリの中で読める文面と食い違うためです

見た目は GitHub Pages の既定のテーマ（Primer）の CSS を使い、レイアウトだけ `_layouts/default.html` で差し替えています。
