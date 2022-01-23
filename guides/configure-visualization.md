# Configure visualization

### Node Caption

```javascript
  node: {j
    caption: ['id'],
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



### Node Opacity <a href="#node-icon" id="node-icon"></a>



### Node Icon <a href="#node-icon" id="node-icon"></a>

