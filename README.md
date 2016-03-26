# hackerman

Hackerman will hack you back in time, till the time when the web development was simple.

![Hackerman](http://i.imgur.com/Hfzf14T.gif)

Hackerman will allow you to start your development in seconds.

### Do you want to code your ReacJS SPA?

1. run ```hackerman generate react-app``` to generate index.html, main.js, App.jsx
2. start devserver - ```hackerman devserver src/main.js```
3. open localhost:3030 in your browser
4. run ```hackerman build src/app.js``` to create production build

What will you get out of the box:

1. ES6 support (babel stage1 && react)
2. less, sass support
3. eslint support (airbnb rules)
4. webpack-dev-server
5. hot-reload
6. postcss autoprefixer
7. image packing into base64
8. development and production modes

### Override defaults

1. .eslintrc  
2. .babelrc
3. webpack.config.js

### Customization

if you want to create own hackerman setup for usage in your company. It extremely simple.

1. ```mkdir webbylab-hackerman```
2. ```cd webbylab-hackerman```
3. ```npm init```
4. ```npm install hackerman --save```
5.


### lookup priority

1. hackerman default configs
2. hackerman-configuration package
3. projects configs
