"# react-do-zero" 


Sequência de comandos utilizados na instalação e configuração

yarn init -y

yarn add react react-dom

yarn add @babel/core @babel/preset-env @babel/preset-react webpack webpack-cli

yarn add @babel/cli

yarn babel src/index.js --out-file public/bundle.js

yarn add babel-loader

yarn webpack --node development

yarn add webpack-dev-server -D

yarn webpack-dev-server --mode development
