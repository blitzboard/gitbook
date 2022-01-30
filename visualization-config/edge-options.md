# Edge options

### Caption

By default, only the **edge label** is shown.

To show edge IDs or node labels, you can set `id` or `label`, respectively. To show values of edge properties, you can list the node properties.

Show edge IDs, edge labels, and the values of `since` property.

```javascript
  edge: {
    caption: ['id', 'label', 'since'],
  },
```

### Color

By default, edge colors are **selected automatically** based on labels.

To set custom colors, you can fill color string values or select the edge properties which hold color string values.

Set a single color for all edges with any label.

```javascript
    color: 'red',
```

Set single colors for the edges with particular labels.

```javascript
    color: {
      'person': 'red',
      'car': 'blue',
    },
```

Set the values of `color` property for all edges with any label.

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

### Opacity <a href="#node-icon" id="node-icon"></a>

By default, edge opacity is set to **`1`** (= not transparent at all).

To set opacity, you can set opacity number values or select the edge properties which hold opacity number values.

Set opacity for all nodes with any label.

```javascript
    opacity: 0.5,
```

Set opacity for the nodes with particular labels.

```javascript
    opacity: {
      'person': 0.5,
      'car': 0.8,
    },
```

Set the values of `opacity` property for all nodes with any label.

```javascript
    opacity: '@opacity',
```

The combination of the above.&#x20;

```javascript
    opacity: {
      'person': 0.5,
      'car': '@opacity',
    },`
```

### Saturation

By default, node saturation is set to **`100%`** (= fully colorful).

To set saturation, you can set opacity number values or select the node properties which hold opacity number values.

Set saturation for all nodes with any label.

```javascript
    saturation: '100%',
```

For setting by labels or using property values, please see the [Color section](edge-options.md#node-color).&#x20;

### Brightness

By default, node brightness is set to **`37%`**.

To set brightness, you can set opacity number values or select the node properties which hold opacity number values.

Set brightness for all nodes with any label.

```javascript
    brightness: '37%',
```

For setting by labels or using property values, please see the [Color section](edge-options.md#node-color).&#x20;
