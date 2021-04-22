# basics

## SASS とは？

- Syntactically Awesome StyleSheets
- CSS Preprocessor / Precompiler
- CSS 機能を強化する

- 拡張子： .scss , .sass ※scss が優先

- コンパイルされて css file に変換される
- Sass コンパイラーは複数(cli , GUI)

## 機能

- 変数
- ネスト
- Partials / Imports
- Functions / Mixins
- Conditionals
- Inheritance
- Operators / Calculations
- Color Functions

## 環境構築

```
npm init -y
npm install node-sass

// package.json修正
npm run sass
※これで常にウォッチされている状態なので、live serverで表示中にscss修正するとサイトにリアルタイムで反映される

```
