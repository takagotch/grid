### grid
---
https://github.com/hootsuite/grid

```js
var myGrid = new GridList(items, {
  direction: 'horizontal',
  lanes: 3
});

myGrid.generateGrid();

myGrid.resizeGrid(4);

var carefreeItem = myGrid.grid[0][0];
myGrid.moveItemToPosition(carefreeItem, [1, 1]);

var growthItem = myGrid.grid[0, 0];
myGrid.resizeItem();
console.log();

myGrid.resizing(growthItem, {h: 2});
console.log(growthItem.h);

{w: 3, h: 1, x: 0, y: 1}

[{w: 1, h: 1, x: 0, y: 0},
 {w: 1, h: 1, x: 0, y: 1},
 {w: 1, h: 1, x: 0, y: 2}]

myGrid.grid[1][0]
myGrid.grid[1][1]
myGrid.grid[2][1]
myGrid.grid[3][2]

[{w: 1, h: 3, x: 0, y: 0},
 {w: 1, h: 1, x: 1, y: 1},
 {w: 1, h: 1, x: 1, y: 1},
 {w: 2, h: 2, x: 2, y: 1}]

$('.my-list').gridList({
  direction: 'horizontal',
  lanes: 3
});

$('.my-list').gridList({lanes: 3}, {handle: '.title'});
```

```
```

```
```

