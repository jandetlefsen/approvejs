# ApproveJs
#### A simple validation library that doesn't interfere
![semver 1.0.4](https://img.shields.io/badge/semver-1.0.4-green.svg) [![Build Status](https://travis-ci.org/CharlGottschalk/approvejs.svg?branch=master)](https://travis-ci.org/CharlGottschalk/approvejs)

When I say, doesn't interfere, I mean it doesn't attach itself to input change events or form submit events. It also doesn't manipulate the DOM for you by automatically displaying errors.

ApproveJs exposes a single method, `value()` and leaves you to decide when a value is validated and how errors are displayed.

Using ApproveJs, you can automate validation however you please.

Personally, I use [Vue.js](http://vuejs.org/guide/events.html) bindings to handle when validation occurs and how errors are displayed.

If you like to be in control or have a little OCD like me, ApproveJs is for you.

ApproveJS is also easily extended with [custom tests](http://charlgottschalk.co.za/projects/approvejs/docs/1.0.4/custom-tests).

---

### Installation

##### Standalone

<a href="https://github.com/CharlGottschalk/approvejs/releases"
style="color: #fff; background-color: #6496c8; margin: 0 10px 0 0; padding: 15px 45px; font-size: 32px; line-height: 1.8; box-shadow: 0 2px 2px rgba(204, 197, 185, 0.5);"> Download Latest Release </a>

Add a `script` tag to the library before the end of your closing `<body>` tag

```html
<script src="path/to/approve.min.js"></script>
```

##### Bower

In your terminal run:

```
$ bower install approvejs
```

Add a `script` tag to the library before the end of your closing `<body>` tag

```html
<script src="path/to/bower/approvejs/dist/approve.min.js"></script>
```


##### Node

In your terminal run:

```
$ npm install approvejs
```

Require `approvejs`.

```javascript
var approve = require('approvejs');
```

---

View the [project page](http://charlgottschalk.co.za/projects/approvejs) for [demos](http://charlgottschalk.co.za/projects/approvejs/demo) and [documentation](http://charlgottschalk.co.za/projects/approvejs/docs) on rules and extending ApproveJs with your own tests.

If you would like to contribute to the project, please read [contributing](http://charlgottschalk.co.za/projects/approvejs/docs/contributing).