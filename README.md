# Simpla Demo Helper
![Version][bower-badge] [![Build status][travis-badge]][travis-url] [![Bower dependencies][bowerdeps-badge]][bowerdeps-url] ![Size][size-badge] [![Published][webcomponents-badge]][webcomponents-url]

Simpla-demo-helper sets up an environment for Simpla element demos. It imports Simpla, sets up a dummy project, and adds an edit mode toggle control to the page.

<!---
```
<custom-element-demo>
  <template>
   <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="simpla-demo-helper.html">
    <link rel="import" href="../simpla-text/simpla-text.html">
    <style>
      body {
        font-family: sans-serif;
        padding: 1rem;
      }
      
      simpla-text {
        margin: 1.5rem 0.2rem 0;
      }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<simpla-demo-helper></simpla-demo-helper>

<!-- Element demo -->
<simpla-text path="/example"></simpla-text>
```

## Installation & usage

Install simpla-demo-helper with Bower (Yarn support coming soon)

```sh
$ bower install simpla-demo-helper --save-dev
```

Import it into the `<head>` of your element demo page

```html
<link rel="import" href="../../simpla-demo-helper/simpla-demo-helper.html">
```

Then use the element at the top of your page. It will include and setup Simpla for you, and an edit mode toggle control will be available where the element is used.

```html
<simpla-demo-helper></simpla-demo-helper>
```

***

MIT © Simpla

[bower-badge]: https://img.shields.io/bower/v/simpla-demo-helper.svg
[bowerlicense-badge]: https://img.shields.io/bower/l/simpla-demo-helper.svg
[travis-badge]: https://img.shields.io/travis/SimplaElements/simpla-demo-helper.svg
[travis-url]: https://travis-ci.org/SimplaElements/simpla-demo-helper
[bowerdeps-badge]: https://img.shields.io/gemnasium/SimplaElements/simpla-demo-helper.svg
[bowerdeps-url]: https://gemnasium.com/bower/simpla-demo-helper
[size-badge]: https://badges.herokuapp.com/size/github/SimplaElements/simpla-demo-helper/master/simpla-demo-helper.html?gzip=true
[webcomponents-badge]: https://img.shields.io/badge/webcomponents.org-published-blue.svg
[webcomponents-url]: https://www.webcomponents.org/element/SimplaElements/simpla-demo-helper
