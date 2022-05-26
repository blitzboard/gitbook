# Share

## Share as a URL

![](<../.gitbook/assets/Screen Shot 2022-03-20 at 12.55.59.png>)

## Export into a zip file

![](<../.gitbook/assets/Screen Shot 2022-03-20 at 12.51.41.png>)

This option exports a dataset and configuration settings into a single zip file. This is useful to keep the package permanently on your local disk and to share it with others.

Each zip package contains two files below:

* graph.pg
* config.js

## Import from a zip file

Click the Import button in the menu bar, and upload **a zip file** previously exported.

![](<../.gitbook/assets/Screen Shot 2022-03-20 at 13.00.46.png>)

## Embed into your pages

![](<../.gitbook/assets/Screen Shot 2022-03-20 at 13.05.20.png>)

This option exports a dataset, configuration settings, and essential JavaScript packages together. With this JavaScript file, you can embed the visualization into a HTML code as follows:

Load scripts in the header of the your html:

```html
<script src='https://unpkg.com/vis-network/standalone/umd/vis-network.min.js'></script>
<script src='https://cdn.jsdelivr.net/gh/blitzboard/blitzboard/blitzboard.js'></script>
<script src="https://code.iconify.design/2/2.0.4/iconify.min.js"></script>
```

Place div tag with `id='blitzboard'`:

```html
<div style="width:100%; height: 500px;" id='blitzboard'></div>
```

Download `<name>_<datetime>.js`, and add this file path after the items above:

```html
<script src='./<name>_<datetime>.js'></script>
```

You can also call the API with graph data (in .pg format) and config:

```javascript
let blitzboard = new Blitzboard(document.getElementById('blitzboard'));
blitzboard.update(pg, config);
```
