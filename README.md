# 和食材カレンダー / Washokuzai Calendar

このフォルダの中身を GitHub のリポジトリ直下にアップロードしてください。

## 構成

- index.html … サイト本体（仕組みのみ）
- data/ … 品目データ
  - common.json … 時期・写真（言語に依らない部分）
  - ja.json / en.json / th.json … 言語ごとの訳文
- images/ … 品目の写真
- images/cook/ … 調理法の写真
- favicon.png / apple-touch-icon.png / washokuzai-mark.png … アイコン

## 更新するとき

変更した内容によって、上げるファイルが変わります。

| 変更内容 | 上げるファイル |
|---|---|
| 品目・時期・写真の指定 | data/common.json と data/ja.json |
| 翻訳の修正 | data/(言語).json |
| 機能の追加・修正 | index.html |

管理画面（shun-admin.html）はここに置かないでください。
