# Webpack Course

- instalación
```
    npm i webpack webpacl-cli -D
```
- consola
```
    npx webpack --mode production --config webpack.config.js
```
- script
 ```
    "build": "webpack --mode production"
 ```   
- babel
```
    npm i babel-loader @babel/core @babel/preset-env @babel/plugin-transform-runtime @babel/register -D
```
- HTML
```
    npm i html-webpack-plugin -D
```
- css
```
    npm i mini-css-extract-plugin css-loader -D
```
- stylus
```
    npm i stylus stylus-loader -D
```
- copiar archivos de source a distributions
```
    npm i copy-webpack-plugin -D
```
- fuentes
```
    npm i url-loader file-loader -D
```
- compresión y minificación

```
npm i css-minimizer-webpack-plugin terser-webpack-plugin -D
```
- variables de entorno
```
npm i dotenv-webpack -D
```
- limpiar archivos en producción
```
    npm i clean-webpack-plugin -D
```
- cambio automático
```
primera forma: watch: true
segunda forma: "build:watch": "webpack --watch --config webpack.config.js"
```