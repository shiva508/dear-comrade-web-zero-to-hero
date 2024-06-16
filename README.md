# Welcome

# CSS

### CSS => Cascading Style Sheet

```
h1{
   color: red
}
```

- h1 is called attribute
- color is called property
- red is value

### Combining common styles

```
h1,
h2,
h3,
h4,
p,
li {
  font-family: sans-serif;
}
```

### Descendent selector

```
footer p {
  font-size: 16px;
}
```

```
article footer p {
  font-size: 16px;
}
```

### font-family

### font-weight

### font-size

### text-align

### text-transform

### line-height

### background-color

### color

#### RGB

- Colors in CSS reprsented in R(RED)-G(GREEN)-B(BLUE).
- Value ranges from 0 to 255.
- RGB(120, 230, 180).
- RGB with transparency.
- RGB(120, 230, 180, 0.4).

#### Hexadecimal

- It can be represented in Hexadecimal.
- Value ranges from 0 to ff.

#### Gray Shades

- RGB (0,0,0) / #000
- RGB(255,255,255) / #fff

### border

- It takes three params WIDTH, STYLE, COLOR

```
aside {
  border: 5px solid #1098ad;
}
```

### Psuedo class

```
li:first-child {
  font-weight: bold;
}

li:last-child {
  font-style: italic;
}


li:nth-child(odd) {
  color: red;
}

li:nth-child(3) {
  color: red;
}
article p:first-child {
  color: red;
}

```

### Conflicting styles

##### ID(#)

###### ↓

##### Class(.), pseudo-class(:) selector

###### ↓

##### Element(h,p,div,li) selector

###### ↓

##### Universal(\*) selector
