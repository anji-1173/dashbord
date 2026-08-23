# 開発アプリ一覧 ダッシュボード

これまでハルが作ったウェブアプリ・作品を一覧にしたページです。

## 見る方法

`index.html` をブラウザで開くだけで見られます(ダブルクリックでOK)。

## 新しい制作物を追加したいとき

ハルに「これを追加して」と言ってもらえれば、`index.html` 内の `PROJECTS` にブロックを1つ足します。
ご自身で編集する場合は、`index.html` を開いて `PROJECTS` の配列に以下の形で追加してください。

```js
{
  name: "作品名",
  category: "webapp", // または "stamp"
  desc: "一言説明",
  image: "images/ファイル名.png",
  link: "https://...",
  status: "live", // live=公開中 / sale=販売中 / wip=作成中
  updated: "2026-08-22",
},
```
