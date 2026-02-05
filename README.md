
![image](https://github.com/AkienMain/voronoi-button/blob/main/images/image_001.png?raw=true)

HTMLElement of button devided by voronoi cells.

# How to Use

Use this packege with [mathjs](https://www.npmjs.com/package/mathjs).

```
<script src="https://cdnjs.cloudflare.com/ajax/libs/mathjs/14.8.1/math.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/voronoi-button/voronoi-button.min.js"></script>
```

## HTML example
```
<voronoi-button
    n-cells="3"
    colors="#FFFFCCAF, #FFCCFFAF, #CCFFFFAF"
    color-selected="#FF3939"
    srcs="https://raw.githubusercontent.com/AkienMain/sudoku_solver/refs/heads/master/output/sample.png/output.png, https://github.com/AkienMain/p5js-works/blob/main/work001-voronoi/images/image_001.png?raw=true, https://github.com/AkienMain/yogapose-classification-ocr/blob/main/README_img/004.png?raw=true"
    width="200"
    height="60"
    border-radius="4"
    threshold-sim="0.1"
    onclick="example1(this.index)"
/>
```

# Page

https://www.npmjs.com/package/voronoi-button