[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/jifalops/drag-resize)

# drag-resize
A touch friendly draggable and/or resizable container.

## Installation

```
bower i -S jifalops/drag-resize      # Polymer 2.0 class based
bower i -S jifalops/drag-resize#^0.2 # Polymer 2.0 hybrid (1.x compatible)
```

## Usage
* Set which directions are draggable and which edges are resizable.
  All possibilities are enabled by default.
* Optional: set edge/corner borders, mouse cursors, corner gradient color.
* Optional: listen for `on-resize` or `on-drag` events.

## Demo

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="drag-resize.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->

```html
<drag-resize drag="left right" resize="bottom right">
  <div style="height:100px; width:100px; background-color:lightblue;"></div>
</drag-resize>
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
