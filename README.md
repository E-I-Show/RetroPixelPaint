[README.md](https://github.com/user-attachments/files/32790871/README.md)
# Retro Pixel Paint

ブラウザだけで動く、レトロPC風のドット絵ペイントです。縦長ドットの8色から正方ピクセルの16色まで、昔のパソコンの画面のような絵を描けます。

▶ **使ってみる: https://E-I-Show.github.io/RetroPixelPaint/**

## 特長

- **解像度モード6種類 × カラーモード3種類**
  - 縦長ドット: 640×200・640×400（1ドットが横1×縦2。ダブルハイトかスキャンラインで表示）
  - 正方ピクセル: 320×200・320×400・640×400・640×800
  - 8色デジタル（固定の8色）・8色アナログ（512色から8色）・16色アナログ（4096色から16色）
- パレットの2色をディザで混ぜた中間色、タイルの模様、グラデーションで塗れます
- 表画面と裏画面の2画面があり、どちらにも通常レイヤーと線画レイヤーがあります
- ツール: ペン・消しゴム・直線（連続線）・矩形・楕円・塗潰し・グラデ塗・スポイト・全体移動
- ペンタブレットの筆圧と、スマホ・タブレットのタッチ操作に対応しています
- 日本語と英語の表示を切り替えられます
- デスクトップ版（8色版・16色版）とファイルをやり取りできます（.rp8・.rpp・.pal・.tls）
- HTML 1ファイルだけで動き、ネットワークには接続しません

## 使い方

- 上のページを開くだけで使えます。
- `index.html` をダウンロードして、手元のブラウザで開いても使えます（インターネットにつながっていなくても動きます）。
- 詳しい使い方は、アプリの「ヘルプ → マニュアル」にあります。
- 設定はブラウザに保存されます。絵や設定がどこかへ送られることはありません。

## 保存できるファイル

| 形式 | 内容 |
| --- | --- |
| .rpi | このアプリの形式。モード・両方の画面と線画・パレットなどを全部残します |
| .rp8 | 8色版の形式（640×200・8色のときに書き出せます） |
| .rpp | 16色版の形式（正方ピクセルのときに書き出せます） |
| .pal | パレット |
| .tls | タイルセット |
| .png | 画像として書き出し（PNG などの画像を開くこともできます） |

## 動作環境

Chrome・Edge などの最近のブラウザで動作を確認しています。スマホ・タブレットのタッチ操作にも対応しています。

## ライセンス

[MIT ライセンス](LICENSE)です。使う・改変する・再配布する・商用に使うことが自由にできます（再配布するときは、著作権表示とライセンス文を残してください）。

このアプリで描いた絵の権利は、描いた人のものです。

## 作者

E-I-Show

---

## English

Retro Pixel Paint is a pixel art editor that runs entirely in your browser, in the style of retro Japanese PCs.

- 6 resolution modes (tall dots 640×200 / 640×400, square pixels 320×200 / 320×400 / 640×400 / 640×800) × 3 color modes (8 fixed colors, 8 of 512, 16 of 4096)
- Dithered mid-colors, tile patterns and gradients
- Front and back screens, each with a normal layer and a line-art layer
- Pen pressure and touch support; Japanese and English UI
- Exchanges files with the desktop versions (.rp8, .rpp, .pal, .tls)
- A single HTML file that works offline and never connects to the network

Open the page above, or download `index.html` and open it in a modern browser (tested with Chromium-based browsers such as Chrome and Edge). See Help → Manual in the app for details.

Released under the [MIT License](LICENSE). Pictures you draw with this app belong to you.
