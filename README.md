# &lt;google-webfont-loader&gt;
===============================

See the [component page](http://printminion.github.io/google-webfont-loader) for more information.


## Getting Started
Add it via bower
  "dependencies": {
    "google-webfont-loader": "git@github.com:printminion/google-webfont-loader.git#~1.0.2"
  }
  

## Using
 <google-webfont-loader fonts="Droid Sans,Droid Serif"></google-webfont-loader>

    document.querySelector('google-webfont-loader').addEventListener('fonts-active', function(e) {
        console.log('fonts-active', e.detail.fonts);
    });
    

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install


## Playing With Your Element

If you wish to work on your element in isolation, we recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polyserve

And you can run it via:

    polyserve

Once running, you can preview your element at
`http://localhost:8080/components/google-webfont-loader/`, where `google-webfont-loader` is the name of the directory containing it.

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.



