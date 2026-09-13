# 杉島輝 ポートフォリオサイト

## 中身
- index.html        ページ本体（1ファイル）
- images/           作品画像 21点（JPEG・最大1600px・品質86）

## ローカルで確認する
このフォルダを丸ごと置いて index.html をブラウザで開くだけで表示されます。
（file:// でも動きます。画像は相対パス参照です）

## 公開する
フォルダの中身をそのままアップロードするだけです。ビルド作業は不要です。

- GitHub Pages : リポジトリに push → Settings > Pages で公開
- Netlify      : このフォルダを画面にドラッグ&ドロップ
- Vercel       : フォルダを指定してデプロイ（フレームワーク設定は "Other"）
- レンタルサーバ : FTPでそのまま設置

## 差し替えたいとき
- 作品を足す      : images/ に画像を置き、index.html 内の IMG と WORKS に1行ずつ追加
- 連絡先を入れる  : index.html 内の your@email.com と Instagram / X のリンク（#）を書き換え
- 説明文を直す    : index.html 内の WORKS 配列の d: を編集

## 外部から読んでいるもの
- Google Fonts（Mochiy Pop P One / Zen Maru Gothic / Baloo 2 / Archivo）
オフラインで使う場合はフォントがシステム標準に置き換わります。
