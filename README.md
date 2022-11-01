# react_todo

## 開発環境について

- Node.js 16~
- npm 6.14.5
- MACOS Catalina

## ディレクトリ構造
```
.
├── node_modules
│── publuc
│   ├── index.html
│   └── robots.txt
└── src
      ├── App.css
      ├── App.js
      ├── index.js
      └── sampleApp
          ├── components
          │   ├── DogImage
          │   │   └── index.js
          │   ├── TodoForm
          │   │   └── index.js
          │   └── TodoItem
          │       └── index.js
          └── pages
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
