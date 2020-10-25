# Introduction to WebPack

*WebPack is a module bundler. Its main purpose is to bundle JavaScript files for usage in a browser, yet it is also capable of transforming, bundling, or packaging applications and module dependencies. - WebPack* 

This project introduces WebPack and shows how to get started.

## Build and run the project

Run `npm run build` to build the project. The build artifacts will be stored in the `dist/` directory. Open `public/index.html` in your browser to view the website with its build dependencies.

## Getting started with WebPack

The quickest way of getting started with WebPack is by using the NPM package manager. NPM handles dependencies and scripts used for this project. 

- You can run `npm init -y` to initialize NPM in your current directory.

Further, this sample project uses *lodash* as a dependency to showcase the utilization of  depended modules within your application.

- Install *lodash* by running `npm i lodash`.

To allow dependencies to be correctly resolved from within your modules, it is necessary to bundle your application resources. This is where we require WebPack as an developer dependency.

- WebPack can be installed running `npm install --save-dev webpack webpack-cli`.

Custom loaders defined in the `webpack.config.js ` allow the bundling and referencing of additional resources such as TypeScript, CSS and SASS files.

- WebPack can be installed running `npm install --save-dev css-loader style-loader sass-loader sass`.

## Further help

To get more help on WebPack go check out the [WebPack Documentation](https://webpack.js.org/concepts/).
