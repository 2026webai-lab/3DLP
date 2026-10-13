# ATLAS TO PARADISE — 3Dスクロール LP

スクロールに合わせて96枚のフレームを再生するランディングページ。

## 構成
- `index.html` … 本体（外部ライブラリなし）
- `public/frames/` … WebP連番 96枚（frame_001〜096、100枚未満）
- `source/` … 元動画とJPG連番（公開しない）

## ローカル確認
    python3 -m http.server 8000   # http://localhost:8000

## GitHub Pages
Settings → Pages → Branch: main / (root)
