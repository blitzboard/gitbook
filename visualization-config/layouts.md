# Layouts

### Default layout

```
  layout: "hierarchical",
```

### Hierarchical layout

(Please see [here](https://visjs.github.io/vis-network/docs/network/layout.html) to learn more about each parameter)

```javascript
  layout: "hierarchical",
  layoutSettings: {
    enabled: true,
    levelSeparation: 150,
    nodeSpacing: 100,
    treeSpacing: 200,
    blockShifting: true,
    edgeMinimization: true,
    parentCentralization: true,
    direction: "UD",
    sortMethod: "hubsize",
    shakeTowards: "leaves"
  },
```

### Map layout

```javascript
  layout: 'map',
  layoutSettings: {
    lng: 'prop_long',
    lat: 'prop_lat',
    center: [35.087384224892155, 137.15639550369508],
  }
```

### Custom layout

```javascript
  layout: 'custom',
  layoutSettings: {
    x: 'prop_x',
    y: 'prop_y'
  }
```
