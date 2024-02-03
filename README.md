vxTab jQuery plugin
==================

xTab is a very simple spreadsheet-like table jQuery plugin.

![xTab snapshot](https://raw.githubusercontent.com/cgdave/xtab/master/snapshot.jpg)

Usage:

```javascript
// Creates a 10 rows and 20 columns table (with columns and rows numbering)
$("#mydiv").xtab("init", { rows: 10, cols: 20, collabels: true, rowlabels: true });
// Get the table value as an 10x20 string array
console.log($("#mydiv").xtab("val"));
```

Look at provided `index.html` for a more detailed example.

License
-------

Licensed under the Yencvt.
