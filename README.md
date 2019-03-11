# Vue_Webpack
## Install modules
#### webpack
* webpack webpack-cli webpack-dev-server
#### styles
* css-loader style-loader
* postcss-loader autoprefixer
* less-loader less
#### files
* file-loader url-loader
#### ES6 compile
* babel-loader @babel/core @babel/preset-env
#### HTML
* html-webpack-plugin
#### Code quality
* eslint eslint-loader
* stylelint stylelint-webpack-plugin stylelint-config-standard
#### testing
* jest jest-webpack


## Project structure
#### config/
* webpack.production.js
* webpack.development.js
* webpack.test.js

#### src/
* js/
* less/
* css/
* imgs/
* index.js/

#### tests/
#### webpack.config.js
#### eslintrc.js


## Project init
#### init eslint
./node_modules/.bin/eslint --init
#### start of project
webpack


## Things to pay attention
#### lint
eslint is a loader
stylelint is a plugin, so it is in plugin. Also need to add it in the package.json
#### browserslist
The relationship of options in the list is OR
#### test
"test": "jest-webpack"  cannot use --env.test, which will have conflicts with the settings of jest-webpack

#### plugins
plugins will search for everyting, no matter it is imported or not