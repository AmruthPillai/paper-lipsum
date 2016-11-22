# \<paper-lipsum\>
The Dummy Text Generator Web Component

## Introduction

<p>`paper-lipsum` is a web component created using Polymer to let your display dummy blocks of text on your website using just one tag, instead of having to copy paste the whole block from a website.
<i>It's as easy as 1-2-3.</i></p>

## Installation

Make sure you have npm and bower installed. Then, run this command:

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

<p>You can check this out <strong>in action</strong> on the demo page: <a href="#">some long link here</a></p>

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
