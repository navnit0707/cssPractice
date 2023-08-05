```text
    1. Establish these colors as a CSS global variables.
    2. Display these colors in a series of small boxes(3rem * erem) , one color per box .
    3. put all of those color boxes ,in a row with with a 1rem  gap between
```
## some css used in this project and their explanation 

```

html{
    box-sizing: border-box
}
```

    <text>when we add padding and margin by default the box become bigger , because thats how width is measured , iif we add the above property , the box will not get bigger </text>

```
:root{
--lime :	#A4FFA2;
}
```

`-- is used to create variable , but to use that we can create a class `

example :

```

.lime{
background-color: varibale(--lime);
}

```

selecting all child of some div

```css
colors > * {
}
```

here what the above means is , first of all we reads css from right to left ,

- means everything , > means direct decendent (child)
  so it means select everything that is direct decentent of class colors
