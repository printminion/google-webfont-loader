google-webfont-loader
============

See the [component page](http://russenreaktor.github.io/google-webfont-loader) for more information.

## Getting Started
Add it via bower
  "dependencies": {
    "google-webfont-loader": "git@github.com:russenreaktor/google-webfont-loader.git#~0.0.2"
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
