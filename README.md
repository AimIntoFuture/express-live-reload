# Node.js Express Live server & browser reload
[Original source with more details](https://dev.to/cassiolacerda/automatically-refresh-the-browser-on-node-express-server-changes-x1f680-1k0o)
#### Run commands:

```
npm install -g express-generator
```
```
express my-little-app --view=[view engine, example:'hbs']
```
```
npm install
```
```
npm i -D nodemon livereload connect-livereload
```
**package.json**
```json
"scripts": {
  ... 
  "watch": "nodemon --ext *"
},
```
```
npm run watch
```