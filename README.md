# アバター紹介カードメーカー

[![GitHub Pages](https://img.shields.io/static/v1?label=GitHub+Pages&message=+&color=brightgreen&logo=github)](https://vvylw.github.io/avatar-card-maker)
[![Deploy to GitHub Pages](https://github.com/VvyLw/avatar-introduction-card-maker/actions/workflows/deploy-to-pages.yml/badge.svg)](https://github.com/VvyLw/avatar-introduction-card-maker/actions/workflows/deploy-to-pages.yml)


VRChatアバターの紹介カードをブラウザ上で作成し、PNG画像として書き出せるツールです。
インストールや会員登録は不要で、このHTMLファイルをブラウザで開くだけで使えます。

## 主な機能

- **メイン画像のアップロード**: クリック or ドラッグ&ドロップで画像を選択し、専用エディタでズーム・移動しながら切り抜き
- **表情差分**: 最大3枚まで登録可能。それぞれ個別にトリミングでき、削除ボタンでいつでも差し替え可能
- **基本情報の入力**
  - アバター名 / 説明欄(下記「ルビ記法」対応)
  - 肩書き・サブタイトル / 出身(それぞれ別行で表示され、混同しません)
  - 身長・体重
  - スリーサイズ(B/H/W、任意)
  - セリフ(キャラクターが喋っているように見える吹き出し表示)
- **カードの向き切替**: 縦(4:5)/横(5:4〜16:9、レイアウトも横向き専用に再構成)
- **ルビ(ふりがな)記法**: 説明欄で `[漢字|よみ]` のように書くと、漢字の上に読みが小さく表示されます
  - 例: `[吸血鬼|きゅうけつき]` → 「吸血鬼」の上に「きゅうけつき」と表示
- **表示テーマ切替**: ライト/ダークをワンクリックで切替(左上のアイコン)。選択内容はブラウザに保存され、次回開いたときも復元されます
- **多言語対応**: 日本語 / English / 한국어 / 中文(右上のセレクトで切替。選択内容も保存されます)
- **PNG書き出し**: 「完成」ボタンでカードをPNG画像として保存。ファイル名は書き出し時のシステム時刻(例: `20260904_153045.png`)になります
- レスポンシブ対応(スマートフォン・タブレットでもレイアウト崩れが起きにくいよう調整済み)