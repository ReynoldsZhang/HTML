```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
<!--��ʽ�����ȼ�����������ʽ��Inline style > ���ڲ���ʽ��Internal style sheet >���ⲿ��ʽ��External style sheet > �����Ĭ����ʽ-->
<!--�����ⲿ��ʽ-->
    <link rel="stylesheet" type="text/css" href="Study.css">
<!--�����ڲ���ʽ-->
    <style>
        hr {color:sienna;}
        p {margin-left:20px;}
        body {background-image:url("photo/photo.jpg");}
    </style>

<!--�����ⲿ��ʽ-->
    <link rel="stylesheet" type="text/css" href="Study.css"/>
<!--�����ڲ���ʽ-->
    <style>
        h3 {
            text-align:right;
            font-size:20pt;
        }
    </style>
<!--����h3��ӵ�е���ʽ
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

<!--����������ʽ-->
<p style="color:sienna;margin-left:20px">����һ�����䡣</p>

<div class = "center";>
    �������
</div>
<p class="center">
    ������У�����û������
</p>

</body>
</html>
```
