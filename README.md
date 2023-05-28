npm init

npm i webpack --save-dev

npm i webpack-cli --save-dev

npm i webpack-dev-server --save-dev

npm i @babel/core --save-dev

npm i @babel/preset-env --save-dev

npm i core-js --save

npm i babel-loader --save-dev

npm i html-webpack-plugin --save-dev

npm i css-loader --save-dev

npm i mini-css-extract-plugin --save-dev

npm i postcss-loader --save-dev

npm i autoprefixer --save-dev

npm i cssnano --save-dev



"scripts": {
    "build": "rm -rf dist && webpack --mode production",
    "dev": "webpack serve",
    "predeploy": "npm run build",
    "deploy": "gh-pages -d dist"
  },
