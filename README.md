# \<paper-lipsum\> [![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://beta.webcomponents.org/element/AmruthPillai/paper-lipsum)  
The Dummy Text Generator Web Component

## Introduction

`paper-lipsum` is a web component created using Polymer to let your display dummy blocks of text on your website using just one tag, instead of having to copy paste the whole block from a website.
<i>It's as easy as 1-2-3.</i>

<h3>Take a look at the <a href="https://amruthpillai.github.io/paper-lipsum/">Documentation & Demo</a></h3>

## Installation

Make sure you have <a href="https://nodejs.org/en/">Node/NPM</a> and <a href="https://bower.io/">Bower</a> installed. Then, run this command:

```
bower install --save AmruthPillai/paper-lipsum
```

Import the `webcomponents.js` script to your webpage, if you haven't already:

```
<script src="bower_components/webcomponentsjs/webcomponents-lite.js"></script>
```

Then, import the paper-lipsum component to your webpage:

```
<link rel="import" href="bower_components/paper-lipsum/paper-lipsum.html">
```

That's all you need to start using the `<paper-lipsum>` tag. Magical, isn't it?

## Usage

<p>All you need to do to get some dummy text is:</p>

```
<paper-lipsum></paper-lipsum>
```

<p>I'm not kidding... <strong>that's it!</strong> <small>(I'm starting to sound like I'm overselling this component, aren't I?)</small></p>

<p>But of course, there are a few other ways to manipulate this text too... like displaying a certain number of words:</p>

```
<paper-lipsum words="200"></paper-lipsum>
```

<p>You can check this out <strong>in action</strong> on the GitHub demo page: <a href="https://amruthpillai.github.io/paper-lipsum/">https://amruthpillai.github.io/paper-lipsum/</a></p>

## Contributing
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Build

### Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

### Viewing Your Application

```
$ polymer serve
```

### Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

### Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.

## License

MIT License

Copyright (c) 2016 Amruth Pillai

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
