# daigakusai-demo

大学祭アンケート抽選の演出案（立体のダーツ／賞品の数だけ並ぶカードめくり）のデモです。

- 公開ページ: https://2370058.github.io/daigakusai-demo/
- ファイルは `index.html` の1つだけで完結しています（ブラウザで直接開いても動きます）
- 抽選はページの中だけで行います。本番のアプリ（サーバー・DB）には触りません
- 立体のダーツは [Three.js](https://threejs.org/)（MIT License）を CDN から読み込んで使っています

## 公開のしかた（初回だけ）

Settings → Pages → Build and deployment の Source を「Deploy from a branch」、Branch を `main` / `/ (root)` にして Save。
以後は `main` の `index.html` を更新すると、1〜2分で公開ページに反映されます。
