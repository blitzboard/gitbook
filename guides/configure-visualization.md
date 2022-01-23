# Configure visualization

### Node Caption

By default, no caption is shown.

To show node IDs or node labels, you can set `id` or `label`, respectively. To show values of node properties, you can list the node properties.

Show node IDs, node labels, and the values of `name` property.

```javascript
  node: {
    caption: ['id', 'label', 'name'],
  },
```

### Node Color

By default, node colors are selected automatically based on labels.

To set custom colors, you can fill color string values or select the node properties which hold color string values.

Set a single color for all nodes with any label.

```javascript
    color: 'red',
```

Set single colors for the nodes with particular labels.

```javascript
    color: {
      'person': 'red',
      'car': 'blue',
    },
```

Set the values of `color` property for all nodes with any label.

```javascript
    color: '@color',
```

The combination of the above.&#x20;

```javascript
    color: {
      'person': 'red',
      'car': '@color',
    },
```

### Node Size

By default, node size is set to `25`.

To set custom sizes, you can fill size number values or select the node properties which hold size number values.

Set a single size for all nodes with any label.

```javascript
    size: 15,
```

Set single sizes for the nodes with particular labels.

```javascript
    size: {
      'person': 15,
      'car': 20,
    },
```

Set the values of `size` property for all nodes with any label.

```javascript
    size: '@size',
```

The combination of the above.&#x20;

```javascript
    size: {
      'person': 15,
      'car': '@size',
    },`
```

### Node Shape <a href="#node-icon" id="node-icon"></a>

By default, node shape is set to `dot`.

To set custom shapes, you can fill shape string values or select the node properties which hold shape string values.

* [List of available shapes](https://visjs.github.io/vis-network/examples/network/nodeStyles/shapes.html)

Set a single shape for all nodes with any label.

```javascript
    shape: 'square',
```

Set single sizes for the nodes with particular labels.

```javascript
    shape: {
      'person': 'dot',
      'car': 'square',
    },
```

Set the values of `size` property for all nodes with any label.

```javascript
    shape: '@shape',
```

The combination of the above.&#x20;

```javascript
    shape: {
      'person': 'dot',
      'car': '@shape',
    },`
```

* ### Node Opacity <a href="#node-icon" id="node-icon"></a>



### Node Icon <a href="#node-icon" id="node-icon"></a>

