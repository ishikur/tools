# Tools

便利なツール・Chrome拡張機能を配布するページです。

https://ishikur.github.io/tools/

## ツール一覧

| ツール名 | 説明 |
|---------|------|
| [ovice Reaction Deck](https://github.com/ishikur/ovice-reaction-deck) | oviceでオリジナルリアクションを自由に使えるChrome拡張機能 |

## ツールの追加方法

`index.html` 内の `tool-card` ブロックをコピーして、ツール情報を書き換えてください。

```html
<div class="tool-card">
  <img src="images/your-tool.jpg" alt="ツール名" class="tool-card-image">
  <div class="tool-card-body">
    <h2>ツール名</h2>
    <p>ツールの説明</p>
    <!-- ボタン・使い方など -->
  </div>
</div>
```
