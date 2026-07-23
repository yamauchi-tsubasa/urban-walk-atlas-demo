# Urban Walk Atlas — Public Demo

街歩きの観察を Field Journal と Research Atlas に整理する個人用Webアプリの、ポートフォリオ向け公開デモです。

## 実用版との分離

このフォルダは実用版から独立した静的サイトです。

- ログイン、データベース、APIなし
- 写真・音声アップロードなし
- 秘密鍵、個人情報、実用版URLなし
- GitHub Pagesで動作
- デモで作成したWalkは閲覧者自身のブラウザ内だけに保存

## サンプル

- Delft：元アプリに含まれていたサンプル
- Rotterdam / Leiden：画面構成を示す架空サンプル

後者2件は調査成果ではなく、公開画面にも「架空サンプル」と表示します。

## 構成

    index.html
    assets/css/style.css
    assets/js/app.js
    .gitignore
    .nojekyll
    README.md
    robots.txt

## GitHub Pages

1. Publicリポジトリを作成します。
2. このフォルダの中身を、index.html が最上位になるようアップロードします。
3. Settings → Pages を開きます。
4. Deploy from a branch、main、/(root) を選び、保存します。

ページ遷移はハッシュURLを使うため、GitHub Pagesのサブディレクトリでも動作します。

## 公開前の確認

- 実用版のURL・設定・データ・写真を追加していないか
- サンプルと実際の調査成果が区別されているか
- 再利用を許可する場合は、方針に合う LICENSE を追加したか
