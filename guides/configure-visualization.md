# Configure visualization

### &#x20;<a href="#node-icon" id="node-icon"></a>

### Node Caption <a href="#node-icon" id="node-icon"></a>

```
  node: {
    caption: ['id'],
  },
```

### Node Color <a href="#node-icon" id="node-icon"></a>

Set a single color for the nodes with any label.

```
  node: {
    color: 'red',
  },
```

Set a single color for the nodes with particular labels.

```
  node: {
    color {
      person: 'red',
      car: 'blue',
    },
  },
```

Set the values of `color` property for the nodes with any label.

```
  node: {
    color: '@color',
  },
```

The combination of the above.&#x20;

```
  node: {
    color {
      person: 'red',
      car: '@color',
    },
  },
```

### Node Size <a href="#node-icon" id="node-icon"></a>



### Node Shape <a href="#node-icon" id="node-icon"></a>



### Node Opacity <a href="#node-icon" id="node-icon"></a>



### Node Icon <a href="#node-icon" id="node-icon"></a>

