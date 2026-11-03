# hibi-pages

hibi（日記アプリ）の公開ドキュメント / 静的ファイルホスティング用リポジトリ。

## 配信内容

- `privacy.html` — プライバシーポリシー
- `terms.html` — 利用規約
- `en/privacy.html`・`en/terms.html` — プライバシーポリシー・利用規約の英語版（参考訳・日本語版が優先。[T057]）
- `faq.html`・`notices.html` — よくあるご質問・お知らせ（`notices.html` は `notices.json` を読んで表示）
- `en/faq.html`・`en/notices.html` — FAQ・お知らせの英語版（[T057]。英語のお知らせは `notices.json` の `title_en` と `body_en` が両方あるものだけを出す）
- `notices.json` — アプリ内お知らせ配信用 JSON
- `get.html` — 友達紹介シェアの着地点（`/get`）。OS 判定で各ストアへリダイレクト。⚠ URL 恒久固定・ファイル名変更/ディレクトリ化/削除は禁止（共有済みリンクが全て死ぬため）

## 公開 URL

GitHub Pages（main / root）+ カスタムドメイン `hibi.bmtx.jp` で公開:

- `https://hibi.bmtx.jp/privacy.html`
- `https://hibi.bmtx.jp/terms.html`
- `https://hibi.bmtx.jp/en/privacy.html`・`https://hibi.bmtx.jp/en/terms.html`（英語版）
- `https://hibi.bmtx.jp/faq.html`・`https://hibi.bmtx.jp/notices.html`
- `https://hibi.bmtx.jp/en/faq.html`・`https://hibi.bmtx.jp/en/notices.html`（英語版）
- `https://hibi.bmtx.jp/notices.json`
- `https://hibi.bmtx.jp/get`

旧 URL（`https://kskn.github.io/hibi-pages/...`）はカスタムドメインへ自動リダイレクトされる（GitHub Pages の仕様）。

## 関連

- アプリ本体: `kskn/hibi`（Private）
- お問い合わせ: hibi 用 Gmail（hibi アプリ内設定画面から）
