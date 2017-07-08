[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/idanen/x-counter)
# \<x-counter\>

A simple counter element

## Installation
```
$ bower install x-counter
```

## Usage
```html
<link rel="import" href="bower_components/x-counter/x-counter.html"/>
<!-- ... -->
<!-- later in the document -->
<x-counter count="1" min="0" max="100"></x-counter>
```

## Demo
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="x-counter.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<x-counter count="10" min="0" max="100"></x-counter>
```

## Contributing
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

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

## License
MIT
