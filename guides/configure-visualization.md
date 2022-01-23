# Configure visualization

### Node Caption

```javascript
  node: {j
    caption: ['id'],
  },
```

### Node Color

Set a single color for the nodes with any label.

```javascript
  node: {
    color: 'red',
  },
```

Set a single color for the nodes with particular labels.

```javascript
  node: {
    color {
      person: 'red',
      car: 'blue',
    },
  },
```

Set the values of `color` property for the nodes with any label.

```javascript
  node: {
    color: '@color',
  },
```

The combination of the above.&#x20;

```javascript
  node: {
    color {
      person: 'red',
      car: '@color',
    },
  },
```

### Node Size



### Node Shape <a href="#node-icon" id="node-icon"></a>



### Node Opacity <a href="#node-icon" id="node-icon"></a>



### Node Icon <a href="#node-icon" id="node-icon"></a>

