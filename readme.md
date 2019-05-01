# Example project using [Webpack](https://webpack.js.org/) and [Uikit](https://getuikit.com/)

> Aditional packages with **Babel** giving support to ES 2015 were added also to improve development experience

## Install

**Webpack is required**, can be installed using the following command(global): ``` npm i -g webpack ``` 

- ``` npm i ``` - Install the project dependencies defined into _package.json_

- File `./app/index.js` is the start file for the project. After all changes into `app` and `.html` file, use the following command to build a new file from _webpack_: `npm run build`

## File structure

        /app/index.js //Application entry point
        /dist/bundle.js //File bundle by Webpack