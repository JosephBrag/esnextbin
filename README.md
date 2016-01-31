# ESNextbin

> Create browser programs with [ES2015](https://babeljs.io/docs/learn-es2015/)'s latest features and use modules from [NPM](https://www.npmjs.com/) directly in your browser.

[<img src="https://dl.dropboxusercontent.com/u/100463011/esnextbin-beta-demo.gif" width="650" />](http://esnextb.in)

## How it works?

- The code gets transpiled by [Babel.js](http://babeljs.io/) v6 with `stage-0`, `es2015` and `react` presets enabled
- [Browserify-CDN](https://wzrd.in/) is responsible for importing npm modules and browserifying them on the fly
- [Github Gists](https://gist.github.com/) are used for saving and sharing code sketches

Under the hood it's pure client-side application which is hosted on [GitHub pages](https://pages.github.com/) and is built upon [React.js](https://facebook.github.io/react/).

## Usage

Explore latest JavaScript features with the help of several useful npm modules and when you're ready just save the result and share the link with your team mates or community.

### Guide

1. ESNextbin interface consists of 2 main sections - _"Editor"_ on the left side and _"HTML Preview"_ on the right side
2. There are 3 editors - "Code" (for Javascript), "HTML" (for html layout) and "Package" (`package.json` that gets updated automatically when you're executing the code which imports library from npm). Switch editors to manage specific part of your program
3. Write program in `Code` tab and after you are ready hit `▶ Execute` button to see the result
4. If you have HTML layout or you're manipulating the DOM in your code you'll see the result in _"HTML Preview"_.
5. But all logging, errors and warnings that appear in runtime could be seen ONLY in your browser's console (maybe it's necessary to add "Console" tab?)
6. `Actions` menu provides:
    - saving your code as public and private [gists](https://gist.github.com/) which can be easily shared (please notice that these actions require GitHub account authorization)
    - _"Clean session"_ resets all editors and unauthorizes your GitHub account (if it was connected)

### Demos

There are several some examples for you to play with:

- [React Starter App](http://esnextb.in/?gist=b7e541a42c7c1218cad6&execute=true)

<!-- 
- [React Soundplayer]()
- [Custom CSS]()
- [WebGL]()
- [Canvas]() 
-->

Please suggest what can be improved, report a bug or ask for a missed features while raising an [issue](https://github.com/voronianski/esnextbin/issues).

## References

Inspired by awesomeness of [Babel.js REPL](http://babeljs.io/repl/) and [Requirebin](http://requirebin.com/).

## License

BSD-2-Clause
