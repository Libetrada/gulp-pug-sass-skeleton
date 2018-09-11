# gulp-pug-sass-skeleton

Gulpを使用してPugとSASSの環境を作るリポジトリ。

## インストール

```
npm install
```

## ファイル構成
開発は`/src`ディレクトリ内で、`/dest`ディレクトリに出力

```
.
├── README.md
├── gulpfile.js
├── package.json
└── src/
    ├── _data/
    │   └── site.json
    ├── _includes/
    │   ├── _footer.pug
    │   ├── _header.pug
    │   ├── _layout.pug
    │   ├── _meta.pug
    │   └── _script.pug
    ├── assets/
    │   ├── css/
    │   │   └── common.sass
    │   └── js/
    │       └── common.js
    └── index.pug
```

## 開発タスク
以下のコマンドを実行すると、開発に必要なGulpのタスクがすべて実行されます。

```
npm start
```

