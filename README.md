[English](#en) | [日本語](#jp)
<a id="jp"></a>
# ガチのマジでマークダウンをレンダリングするだけのサイト (Gachi Markdown Editor)

シングルHTMLファイルで動作する、軽量・高機能なMarkdownエディタです。
サーバー不要で動作し、ブラウザさえあればどこでも執筆・プレビューが可能です。

**Live Demo:** [https://md.locknpackn.dev](https://md.locknpackn.dev)

## 特徴 (Features)

* **完全スタンドアロン:** `index.html` 1ファイルのみで動作。インストール不要。
* **リアルタイムプレビュー:** 入力と同時にMarkdownをレンダリング。
* **シンタックスハイライト:** コードブロックを美しく表示 (Highlight.js)。
* **ダイアグラム対応:** Mermaid.js によるフローチャートやシーケンス図の描画。
* **スクロール同期:** エディタとプレビューのスクロール位置をインテリジェントに同期。
* **レスポンシブデザイン:** PCでは左右分割、スマホではハンバーガーメニュー付きの縦表示に自動切り替え。
* **設定の保存:** 執筆内容、テーマ（ダーク/ライト）、フォント設定などをブラウザに自動保存 (LocalStorage)。
* **インポート/エクスポート:** 設定をTOML形式でバックアップ可能。記事を `.md` として保存可能。
* **自己複製機能:** ツール自体をHTMLとしてダウンロードし、オフラインで持ち運び可能。

## 使い方 (Usage)

1.  [Releases](https://github.com/あなたのユーザー名/リポジトリ名/releases) から、またはこのリポジトリの `index.html` をダウンロードします。
2.  ブラウザ（Chrome, Edge, Firefox, Safariなど）で開きます。
3.  書き始めるだけです！

## 使用ライブラリ (Credits)

このプロジェクトは以下の素晴らしいオープンソースライブラリを使用しています。

* [Marked.js](https://github.com/markedjs/marked) (MIT License) - Markdownパーサー
* [Highlight.js](https://highlightjs.org/) (BSD 3-Clause License) - シンタックスハイライター
* [Mermaid.js](https://mermaid.js.org/) (MIT License) - ダイアグラム描画
* [smol-toml](https://github.com/squirrelchat/smol-toml) (MIT License) - TOMLパーサー

## ライセンス (License)

本ソフトウェアは [MIT License](./LICENSE) の下で公開されています。
商用・非商用問わず、どなたでも自由にご利用・改変いただけます。

---
Copyright (c) 2025 @yoshiteru11600

---
<a id="en"></a>
# Gachi Markdown Editor

A high-performance, standalone Markdown editor that runs entirely within a single HTML file.
No installation, no server, and no build process required. Just open it in your browser and start writing.

**Live Demo:** [https://md.locknpackn.dev](https://md.locknpackn.dev)

![Screenshot](https://via.placeholder.com/800x450.png?text=Gachi+Markdown+Editor+Screenshot)
*(Place a screenshot of your editor here)*

## Features

* **Zero Dependencies:** Works with just one `index.html` file. Portable and offline-ready.
* **Real-time Preview:** Instantly renders Markdown as you type.
* **Syntax Highlighting:** Beautiful code blocks powered by [Highlight.js](https://highlightjs.org/).
* **Diagram Support:** Draw flowcharts, sequence diagrams, and more using [Mermaid.js](https://mermaid.js.org/).
* **Sync Scrolling:** The editor and preview scroll bars stay perfectly synchronized (Split view).
* **Responsive Design:** Automatically switches to a mobile-friendly vertical layout with a hamburger menu on smaller screens.
* **Auto-Save:** Your content and settings (theme, font, etc.) are automatically saved to your browser's LocalStorage.
* **Import/Export:**
    * Export documents as `.md`.
    * Backup/Restore settings via TOML files.
    * **Self-Replication:** You can download the tool itself (`.html`) directly from the menu!

## Usage

1.  Download the `index.html` file from the [Releases](https://github.com/yoshiteru11600/gachi-markdown/releases) page or clone this repository.
2.  Open `index.html` in any modern web browser (Chrome, Edge, Firefox, Safari).
3.  Enjoy writing!

### Keyboard Shortcuts

* `Ctrl + S` / `Cmd + S`: Copy Markdown text to clipboard.
* `Tab`: Insert 4 spaces (Soft tab).

## Configuration

Click the **"Settings" (設定)** button in the header to customize:

* **Theme:** Light / Dark mode.
* **Layout:** Horizontal Split / Vertical.
* **Font:** Choose from Standard, Serif, Monospace, or Handwriting.
* **Custom CSS:** Inject your own CSS to override styles.
* **Headings:** Toggle `#` marks for headers.

## Credits

This project is built with the following amazing open-source libraries:

* [Marked.js](https://github.com/markedjs/marked) (MIT) - Markdown parser
* [Highlight.js](https://highlightjs.org/) (BSD 3-Clause) - Syntax highlighter
* [Mermaid.js](https://mermaid.js.org/) (MIT) - Diagramming and charting tool
* [smol-toml](https://github.com/squirrelchat/smol-toml) (MIT) - TOML parser/stringifier

## License

This project is licensed under the [MIT License](./LICENSE).
Feel free to use, modify, and distribute it for both personal and commercial projects.

---
Created by [@yoshiteru11600](https://twitter.com/yoshiteru11600)