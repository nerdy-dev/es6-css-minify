# JS & CSS Minifier

# Please read the changelog!

[![Visual Studio Marketplace](https://img.shields.io/vscode-marketplace/d/olback.es6-css-minify.svg?style=flat)](https://marketplace.visualstudio.com/items?itemName=olback.es6-css-minify)
[![Visual Studio Marketplace](https://img.shields.io/vscode-marketplace/v/olback.es6-css-minify.svg?style=flat)](https://marketplace.visualstudio.com/items?itemName=olback.es6-css-minify)
[![GitHub package version](https://img.shields.io/github/package-json/v/olback/es6-css-minify/2.0.svg?style=flat&logo=github&label=Github)](https://github.com/olback/es6-css-minify/tree/2.0)
[![Build Status](https://travis-ci.com/olback/es6-css-minify.svg?branch=2.0)](https://travis-ci.com/olback/es6-css-minify)

A simple Javascript & CSS minifier.  
A `Minify` button should appear in the status bar when opening a `.js` or a `.css` file. You can also run `Minify document` by clicking `F1`.

### Loading custom configs
By default the extension will look for `.uglifyrc` and `.cleancssrc`.  
You can change the paths in settings. After changing settings in any of the config files, make sure to reload with `Minify: Reload config`. If the reload fails, make sure you don't have syntax errors in your config. If you want to go back to the default config, rename/delete your config file(s).

### Minify on save, `disabled` by default!
Minify on save can be enabled in settings.  
Make sure to reload your config with `Minify: Reload config` to make sure your changes are applied!  

### Generate source maps
Source maps can be generated by changing `es6-css-minify.genCSSmap` and `es6-css-minify.genJSmap` respectively. Make sure to run `Minify: Reload config`.

#### Dependencies:
* [uglify-es](https://www.npmjs.com/package/uglify-es)
* [clean-css](https://www.npmjs.com/package/clean-css)
