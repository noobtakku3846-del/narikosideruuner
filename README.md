# ゲームだな

ブラウザで遊べるゲームのポータルサイトです(GitHub Pages で公開)。

## 構成
- `index.html` … ゲーム一覧ページ(トップページ)
- `games/<ゲーム名>/index.html` … 各ゲーム本体

## ゲームを追加する方法
1. `games/` の中に新しいフォルダを作り(例: `games/puzzle/`)、ゲームのHTMLを `index.html` という名前で入れる。
2. ルートの `index.html` を開き、`GAMES` の中に1件追加する。

```js
{
  title:"ゲーム名",
  desc:"ひとこと説明",
  path:"games/puzzle/",
  emoji:"🧩",
  colors:["#ffd36a","#ff8a5c"],
  tags:["パズル"],
  added:"2026-11-15"
}
```
新しいものほど上に並び、追加から30日間は NEW バッジが付きます。
