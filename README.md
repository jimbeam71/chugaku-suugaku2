# 中学数学 レベル2（負の数のかけ算・わり算、累乗、文字の入り口）

公開URL: https://chugaku-suugaku2.senta1111.workers.dev/

- 配信するのは `public/index.html` の1枚だけ（KaTeXの式表示も中に入っている）。
- 内容: かけ算・わり算（符号のルール）/ 累乗と順序 / ＝と文字。全14ステップ・91問。
- 問題を直す・足すとき: `tools/gen2.js` を直す。
  1. `cd tools`
  2. `node gen2.js`（`src/data.js` を作る）
  3. `node check.js`（ALL OK が出ること）
  4. `node build.js --repo`（`tools/public/index.html` を作る）→ `public/index.html` に置きかえる
