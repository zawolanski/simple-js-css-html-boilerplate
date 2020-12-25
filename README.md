# JS CSS HTML boilerplate
HTML, CSS, JS boilerplate to create simple and easy apps

## Features

1. Live reloading with **browser-sync** on 3000 port
1. SCSS to CSS transpilation, autoprefixing, optimization, and minification
1. ES6+ to ES5 transpilation and minification
1. Write your own HTML modules and import them to pages located in <code>src</code> folder, pass 'props' to modules and use expressions

## Usage

1. Write your HTML pages in  `/` folder
1. Write your SCSS code in `src/styles` folder
1. Write your JS code in `src/js` folder
1. Write your HTML modules in `src/modules` folder

## Available commands

1. `npm start` - command starts your project. SCSS is parsing to CSS, JS isn't minified and HTML is compiled
1. `npm run build:all` - command builds our application.
  1. CSS is minified, transpiled and optimazed
  1. JS is minified and transpiled
  1. HTML is compiled
  
## HTML Modules - [posthtml](https://github.com/posthtml/posthtml)

Applied plugins:

1. posthtml-expression - [link](https://github.com/posthtml/posthtml-expressions)
1. posthtml-modules - [link](https://github.com/posthtml/posthtml-modules)
1. posthtml-include - [link](https://github.com/posthtml/posthtml-include)
