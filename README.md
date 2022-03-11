# compornent（共通部品）

## 概要

- スマートスクロール用のボタンを css で表現してます。
- div タグにしてるけど、button で作成した方が良かったかな？

## 仕様

- スマホファースト
- rem 記述
- ルートフォントを vw で設定していることから PC サイズのレイアウトをタブレットで表示させることが出来ます（rem で書いた場合のみ）。
- レスポンス対応してるので、表示崩れはしません。
- 擬似要素で上三角を表現してます。
- display は inline-block を使用してるので、text-align で整列可能です。

## 注意事項

- xxx

## 使い方

- 「copy start」から「copy end」をコピペ。
- css: src -> module -> arrow をコピペ。

## イメージ画像
<img width="405" alt="image" src="https://user-images.githubusercontent.com/99580997/157858220-013190d7-0198-4fb0-a2b0-eb979529a442.png">
<img width="785" alt="image" src="https://user-images.githubusercontent.com/99580997/157858260-7b3028db-7835-4fd6-8515-a2c93e6f0a1f.png">
<img width="1239" alt="image" src="https://user-images.githubusercontent.com/99580997/157858306-12696f8f-5533-4526-a4e8-a12b31bb801b.png">


## portfolio url:

- https://c-0022.wtb.cfbx.jp/

## 参考にしたサイト

- 【初心者向け】CSS だけで矢印をスタイルしてコーディングを効率化しよう
- https://www.asobou.co.jp/blog/web/style-arrows

## 更新履歴

- 2022/3/11 初版 作成完了

## 環境・使い方

- ダウンロードしたフォルダを開く。
- ターミナルを開き、 npm i とコマンドを入力する。
- node_modules と package-lock.json が生成されるのを確認する。
- 「 npx gulp 」とコマンドを入力すると動き出します。

## 備考
