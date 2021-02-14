## React, TypeScript, Webpack 最小構成

- ライブラリのインストール

react
```
npm i @type/react @type/react-dom react react-dom
```
webpack
```
npm i -D webpack webpack-cli typescript ts-loader
```

- tsconfig.json 作成
```
tsc --init
```
```
"jsx": "react",  # コメントイン忘れない
```

- webpack.config.js 作成
