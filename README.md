# react_todo

## 開発環境について

- Node.js 16~
- npm 6.14.5
- MACOS Catalina

## ディレクトリ構造
```
.
├── node_modules
├── public
│     ├── index.html
│     └── robots.txt
└── src
      ├── App.css
      ├── App.js
      ├── index.js // 全体に適用したいパッケージやCSS、インポートしたコンポーネントを読み込む
      └── sampleApp // 完成品がはいったディレクトリ
          ├── components // ページを構成する部品のコンポーネントを格納
          │   ├── DogImage
          │   │   └── index.js
          │   ├── TodoForm
          │   │   └── index.js
          │   └── TodoItem
          │       └── index.js
          └── pages // ページを構成するコンポーネントを格納
              └── App
                  ├── index.js
                  └── style.css
```

## プロジェクトのセットアップ

1. パッケージのインストール  
```sh
$ npm i
```

2. Reactアプリのインストール
```sh
$ npx create-react-app react-todo --use-npm
```

### 開発時に実行

```shell
npm start
```
