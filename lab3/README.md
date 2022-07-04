## Exercise 1/ Float boxes: To satisfy the criteria, I add a new class called **break** to the fourth div and modify the other css elements as follows:

```css
#outer {
  border: 2px dashed black;
  overflow: hidden;
  padding: 10px;
}
.box {
  width: 100px;
  height: 100px;
  background-color: black;
  margin: 10px;
  float: left;
}
.break {
  clear: left;
}
```

## Exercise 2/ Menu: To complete this experiment, I add the following CSS elements. I utilize 'display: inline' in particular to adjust the location of li.
```css
ul {
  background-color: red;
  padding: 20px;
  text-align: center;
}

li {
  display: inline;
  border: 1px solid black;
  padding: 10px;
  background-color: white;
}
```

## Exercise 3/ Layout 2: To complete the experiment, I add the following CSS elements. I use 'float: right' to position the first and second columns to the right of the third column.

```css
#container {
  background-color: lightgray;
  overflow: hidden;
  padding: 10px;
  width: 500px;
}
#column1, #column2 {
  background-color: lightblue;
  float: right;
  margin-left: 10px;
  width: 100px;
}
h1 {
  background-color: yellow;
}
```
