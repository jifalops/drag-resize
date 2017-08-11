[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/jifalops/drag-resize)

# drag-resize
A touch friendly resizable container with resize events.

## Installation

```
bower i -S jifalops/drag-resize        # Polymer 2.0 class based
```

## Usage
* wrap the content you want to be resizable.
* set which edges are resizable (defaults to `right bottom`)
* listen for `on-resize` if desired.

## Demo

<!--
```
<custom-element-demo>
  <dom-bind>
    <template is="dom-bind">
      <script src="../webcomponentsjs/webcomponents-lite.js"></script>
      <link rel="import" href="drag-resize.html">
      <custom-style>
        <style is="custom-style">
          drag-resize {
            --drag-resize-edge-size: 6px;
            --drag-resize-corner-border: 2px solid black;
          }
          .content {
            height: 100px;
            width: 100px;
            background-color: blue;
          }
        </style>
      </custom-style>
      <next-code-block></next-code-block>
    </template>
  </dom-bind>
</custom-element-demo>
```
-->

```html
<drag-resize><div class="content"></div></drag-resize>
```

Full demo:
[webcomponents.org](https://www.webcomponents.org/element/jifalops/drag-resize/demo/demo/index.html)
| [github](https://jifalops.github.io/drag-resize/components/drag-resize/demo/).

API: [webcomponents.org](https://www.webcomponents.org/element/jifalops/drag-resize/drag-resize)


## Contributing

1. Fork it on Github.
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## License

[MIT](https://opensource.org/licenses/MIT)
