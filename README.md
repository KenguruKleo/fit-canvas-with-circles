## Randomly fit circles into canvas

Example fit canvas:

![Example image](example/example-img.png?raw=true "Example")

For initial settings:

```
"RADIUS": 76,
	"CANVAS_WIDTH": 2800,
	"HEIGHT_START": 40,
	"HEIGHT_FINISH": 400,
	"INITIAL_PADDING": 5,
	"PADDING_INCREMENT": 1
```

Example result:

```
const CANVAS_WIDTH = 2800;
const RADIUS = 76;
const PADDING = 42;

const bubbleSpecs = [
    { x: 2164, y: 267, s: 0.6 },
    { x: 2687, y: 233, s: 0.6 },
    { x: 628, y: 218, s: 1 },
    { x: 449, y: 86, s: 1 },
    { x: 681, y: 382, s: 0.6 },
    { x: 1942, y: 168, s: 0.8 },
    { x: 1161, y: 372, s: 0.8 },
    { x: 1449, y: 146, s: 0.6 },
    { x: 960, y: 283, s: 0.8 },
    { x: 34, y: 340, s: 1 },
    { x: 811, y: 137, s: 0.8 },
    { x: 347, y: 386, s: 1 },
    { x: 2308, y: 122, s: 0.6 },
    { x: 1560, y: 362, s: 0.8 },
    { x: 525, y: 378, s: 0.6 },
    { x: 133, y: 168, s: 0.6 },
    { x: 1789, y: 380, s: 1 },
    { x: 1314, y: 230, s: 0.8 },
    { x: 2610, y: 366, s: 0.8 },
    { x: 1156, y: 209, s: 0.6 },
    { x: 2430, y: 223, s: 0.6 },
    { x: 1663, y: 205, s: 0.8 },
    { x: 2316, y: 339, s: 0.6 },
    { x: 270, y: 225, s: 0.8 },
    { x: 2627, y: 55, s: 0.6 },
    { x: 1048, y: 43, s: 0.6 },
    { x: 26, y: 42, s: 1 },
    { x: 2154, y: 45, s: 0.8 },
    { x: 1985, y: 387, s: 0.8 },
    { x: 2776, y: 369, s: 0.8 },
    { x: 1369, y: 374, s: 0.6 },
    { x: 1292, y: 44, s: 0.6 },
    { x: 1717, y: 66, s: 0.6 },
    { x: 249, y: 41, s: 0.8 },
    { x: 2790, y: 84, s: 1 },
    { x: 2475, y: 80, s: 0.8 },
    { x: 811, y: 327, s: 0.6 },
    { x: 2447, y: 390, s: 0.6 },
    { x: 673, y: 44, s: 0.8 },
    { x: 461, y: 259, s: 0.6 },
    { x: 1580, y: 74, s: 0.6 },
    { x: 2164, y: 400, s: 0.6 },
    { x: 1848, y: 47, s: 0.6 },
];

```
