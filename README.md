[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/jifalops/drag-resize)

# drag-resize
A touch friendly draggable and/or resizable container.

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
      <next-code-block></next-code-block>
      <script>
        var dynamic = document.getElementById('dynamic');
        var drag = document.getElementById('drag');
        var resize = document.getElementById('resize');
        var edge = document.getElementById('edge');
        var corner = document.getElementById('corner');
        var color = document.getElementById('color');
        var handle = document.getElementById('handle');
        function update() {
          dynamic.drag = drag.value;
          dynamic.resize = resize.value;
          dynamic.updateStyles({
            '--drag-resize-edge-border': edge.value,
            '--drag-resize-corner-border': corner.value,
            '--drag-resize-corner-color': color.value,
            '--drag-resize-handle-size': handle.value,
          });
        }
        function reset() {
          dynamic.reset();
        }
      </script>
    </template>
  </dom-bind>
</custom-element-demo>
```
-->

```html
<drag-resize id="dynamic">
  <div style="height:100px; width:100px; background-color:lightblue;"></div>
</drag-resize><br/>
<input id="drag" value="up down left right"/> Drag<br/>
<input id="resize" value="top bottom left right"/> Resize<br/>
<input id="edge" value="1px dashed #333"/> Edge border<br/>
<input id="corner" value="1px solid #333"/> Corner border<br/>
<input id="color" value="#666"/> Corner color<br/>
<input id="handle" value="8px"/> Resize handle height/width<br/>
<button onclick="reset()">Reset size/pos</button> &nbsp;
<button onclick="update()">Update</button>
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
