# min-gulp for php and sass

phpとsassを使うときのGulpの最小開発環境。
* scssは `/assets/scss/` -> `/assets/css/` に出力。
* scssとphpが更新された時にbrowser-syncでリロード。

## インストール
1. clone
2. git init

## 使い方
1. mamp等でサーバを立てる
2. 立てたサーバにフォルダを置く
3. gulpfile.js内のproxyを変更
4. npx gulp
これでBrowserSyncとscssのコンパイルが動きます。

gulpfile.jsを変更したらコマンドプロンプトの処理を`Ctrl+C`で一度止め、再度`npx gulp`。


