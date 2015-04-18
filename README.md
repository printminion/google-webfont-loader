google-webfont-loader
============

See the [component page](http://polymerlabs.github.io/google-webfont-loader) for more information.

## Getting Started
Add it via bower
  "dependencies": {
    "webfontloader": "typekit/webfontloader#~0.0.1"
  }
  

## Using
 <google-webfont-loader fonts="Droid Sans,Droid Serif"></google-webfont-loader>

    document.querySelector('google-webfont-loader').addEventListener('fonts-active', function(e) {
        console.log('fonts-active', e.detail.fonts);
    });
    
### web-component-tester

The tests are also compatible with [web-component-tester](https://github.com/Polymer/web-component-tester). You can run them on multiple local browsers via:

```sh
npm install -g web-component-tester
wct
```
