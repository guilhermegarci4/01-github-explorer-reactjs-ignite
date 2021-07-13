yarn init -y // Iniciar o package.json

yarn add react // Instalar a biblioteca React
yarn add react-dom // Instalar o DOM (Permite que o react trabalhe com arvore de 
skill do HTML)

ESTRUTURA
|
|_ public
|_ src

# Babel
yarn add @babel/core @babel/cli @babel/preset-env -D

> babel core (core)
> babel cli (usando em linha de comando)
> babel preset-env (identifica qual o ambiente)

yarn babel src/index.js --out-file dist/bundle.js

# Webpack
yarn add webpack webpack-cli -D   
yarn add babel-loader -D 
yarn webpack
yarn add html-webpack-plugin -D
yarn add webpack-dev-server -D 

# ENV
yarn add cross-env -D 

# Importando CSS
yarn add style-loader css-loader -D   

# SAAS
yarn add node-sass -D
yarn add sass-loader -D     

# Refresh
yarn add -D @pmmmwh/react-refresh-webpack-plugin react-refresh

# Typescript
yarn add typescript -D 
yarn tsc --init
yarn add @babel/preset-typescript -D  
yarn add @types/react-dom -D 
yarn add @types/react -D 