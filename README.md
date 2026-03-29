# Markdown Viewer

ブラウザ上で動作するMarkdownビューア・エディタです。単一のHTMLファイルで完結しており、サーバー不要でローカルでもGitHub Pagesでもすぐに使えます。

## デモ

https://norio-hanafusa.github.io/markdown-viewer/index.html

## 機能

- Markdownのリアルタイムプレビュー
- シンタックスハイライト（highlight.js）
- 数式表示（MathJax）
- Mermaid図表対応
- ダークモード切り替え
- 縦置き/横置きレイアウト切り替え
- 表示倍率の変更（80%〜120%）
- Markdownツールバー（見出し、太字、斜体、リスト、表など）
- ファイルの読み込み・保存・ドラッグ&ドロップ対応
- HTML / DOCX形式へのエクスポート
- 文字数・行数・トークン数の表示
- 目次の自動生成
- AI統合（Gemini APIによる要約、ChatGPT/Claude/Geminiへのリンク）

## 使い方

### ローカルで使う

`index.html`をブラウザで開くだけで使えます。

### GitHub Pagesで使う

1. このリポジトリをフォークまたはクローン
2. Settings > Pages > Branch を `main` に設定
3. 公開されたURLにアクセス

### AI要約機能

1. 「AI統合」メニューから「APIキー設定」をクリック
2. Google AI (Gemini) のAPIキーを入力
3. 「AI要約を実行」で内容を箇条書きで要約

※ APIキーはブラウザのメモリにのみ保持され、外部に保存されません。

## 開発について

本プロジェクトは、ChatGPT・Gemini・Claudeを活用した **Vibeコーディング** によって作成されました。

## License

This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.

Copyright (c) 2026 norio-hanafusa

### Third-Party Licenses

This project depends on the following open-source libraries.
Users and redistributors must comply with each library's license terms.

| Library | License | URL |
|---|---|---|
| marked | MIT | https://github.com/markedjs/marked |
| highlight.js | BSD 3-Clause | https://github.com/highlightjs/highlight.js |
| MathJax | Apache 2.0 | https://github.com/mathjax/MathJax |
| Mermaid | MIT | https://github.com/mermaid-js/mermaid |
| html-docx-js | MIT | https://github.com/evidenceprime/html-docx-js |
