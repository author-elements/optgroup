# AuthorOptgroupElement [![](https://data.jsdelivr.com/v1/package/npm/@author.io/element-optgroup/badge)](https://www.jsdelivr.com/package/npm/@author.io/element-optgroup?path=dist) [![Build Status](https://travis-ci.org/author-elements/optgroup.svg?branch=master&style=for-the-badge)](https://travis-ci.org/author-elements/optgroup)

<!-- TODO: Add description -->

![Source Size](https://img.shields.io/github/size/author-elements/optgroup/src/element.js.svg?colorB=%23333333&label=Source&logo=JavaScript&logoColor=%23aaaaaa&style=for-the-badge) ![Deliverable Size](https://img.shields.io/bundlephobia/minzip/@author.io/element-optgroup.svg?colorB=%23333333&label=Minified-Gzipped&logo=JavaScript&style=for-the-badge) ![npm](https://img.shields.io/npm/v/@author.io/element-optgroup.svg?colorB=%23333&label=%40author.io%2Felement-optgroup&logo=npm&style=for-the-badge)

We're using BrowserStack to make sure these components work on the browsers developers care about.

<a href="https://browserstack.com"><img src="https://github.com/author-elements/optgroup/raw/master/browserstack.png" height="30px"/></a>

## Usage

There are 4 versions of this element:

1. *author-optgroup.min.js* (ES6 Minified for Production)
1. _author-optgroup.js_ (ES6 Unminified for Debugging)
1. *author-optgroup.es5.min.js* (ES5 Minified for Production)
1. _author-optgroup.es5.js_ (ES5 Unminified for Debugging)

Each version has it's own source map, so it's always possible to trace activity back to a specific code block in the source.

You only need to choose one of these files. If you need to support Internet Explorer, older versions of Chrome/Firefox/Safari, then you likely need the ES5 version.

*Via Global CDN*

```html
<html>
  <head>
    <script src="https://cdn.author.io/author-elements/base/1.0.0/author-base.min.js"></script>
    <script src="https://cdn.author.io/author-elements/optgroup/x.x.x/author-optgroup.min.js"></script>
  </head>
</html>
```

*Via npm*

If the [base class](https://github.com/author-elements/base) is not yet installed, install it:

`npm install @author.io/element-base -S`

Next, install the optgroup module locally:

`npm install @author.io/element-optgroup -S`

Then include them in your HTML:

```html
<html>
  <head>
    <script src="./node_modules/@author.io/element-base/dist/author-base.min.js"></script>
    <script src="./node_modules/@author.io/element-optgroup/dist/author-optgroup.min.js"></script>
  </head>

  <body>

  </body>
</html>
```
