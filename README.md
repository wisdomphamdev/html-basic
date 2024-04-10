## HTML Basic

## cấu trúc HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>

```

- Element (phần tử): `<tag>` `h1` `p` `ul` `li`
- Attribute (thuộc tính): `href` `src` `alt` 

## id and class
- id là duy nhất 
- class có thể có nhiều 
## các kiểu style 
- inline 
- internal
- external
## mức độ ưu tiên css
>  inline -> id -> class -> thẻ -> *

```
<!-- inline -->
 <h1 style="color:blue">inline</h1>
 <!-- class -->
 <h1 class="h1">inline</h1>

 .h1{
    color:red;
 }
 <!-- id -->
 <h1 id="h1">inline</h1>
 #h1{
    color:green;
 }
 <!-- thẻ -->
 <h1>inline</h1>
 h1{
    color:yellow;
 }
```



> keyword `!important` là cao nhất 

## các tag phổ biến
- `h1 , h2 , h3 , h4, h5, h6`
- `p`
- `a`
- `br`
- `div`
- `span`
- `table`
- `tr`
- `th`
- `td`
- `ul`
- `ol`
- `li`
- `strong`
- `b`
- `i`
- `ins`
- `del`
- `sub`
- `sup`
- `small`
- `mark`
- `hr`

## block vs inline
- block :` <p>, <h1>, <h2>, <h3>, <h4>, <h5>, <h6>, <ul>, <ol>, <hr /> , <div>`
- inline :` <b>, <i>, <em>, <strong>, <sup>, <sub>, <small>, <li>, <ins> <del>`
> block có thể set height với width còn inline thì không .
