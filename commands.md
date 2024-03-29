## Criando estrutura do projeto
1. yarn init -y
2. yarn add react
3. yarn add react-dom

## Configurando Babel
4. yarn add @babel/core @babel/cli @babel/preset-env -D
  - yarn babel src/index.js --out-file dist/bundle.js
5. yarn add @babel/preset-react -D
  - yarn babel src/index.jsx --out-file dist/bundle.js

## Configurando Webpack
6. yarn add webpack webpack-cli -D
7. yarn add babel-loader -D
  - yarn webpack

## Servindo HTML estático
8. yarn add html-webpack-plugin -D

## Webpack Dev Server
9. yarn add webpack-dev-server -D

## Ambiente dev e produção
10. yarn add cross-env -D

## Importando arquivos CSS
11. yarn add style-loader css-loader -D

## Utilizando SASS
12. yarn add node-sass sass-loader -D

## Fast Refresh no Webpack
13. yarn add -D @pmmmwh/react-refresh-webpack-plugin react-refresh

## TypeScript no ReactJS
14. yarn add typescript -D
15. yarn tsc --init
16. yarn add @babel/preset-typescript -D
17. yarn add @types/react-dom -D