1) yarn init -y
2) yarn add react
3) yarn add react-dom

4) yarn add @babel/core @babel/cli @babel/preset-env -D
  - yarn babel src/index.js --out-file dist/bundle.js
5) yarn add @babel/preset-react -D
  - yarn babel src/index.jsx --out-file dist/bundle.js