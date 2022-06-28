```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
<!--样式的优先级：（内联样式）Inline style > （内部样式）Internal style sheet >（外部样式）External style sheet > 浏览器默认样式-->
<!--这是外部样式-->
    <link rel="stylesheet" type="text/css" href="Study.css">
<!--这是内部样式-->
    <style>
        hr {color:sienna;}
        p {margin-left:20px;}
        body {background-image:url("photo/photo.jpg");}
    </style>

<!--假设外部样式-->
    <link rel="stylesheet" type="text/css" href="Study.css"/>
<!--假设内部样式-->
    <style>
        h3 {
            text-align:right;
            font-size:20pt;
        }
    </style>
<!--最终h3所拥有的样式
color:red;
text-align:right;
font-size:20pt;-->

    <style>
        p.center{
            text-align: center;
        }
    </style>
</head>

<body>

<!--这是内联样式-->
<p style="color:sienna;margin-left:20px">这是一个段落。</p>

<div class = "center";>
    标题居中
</div>
<p class="center">
    段落居中，标题没法居中
</p>

</body>
</html>
```
