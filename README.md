# H5
Just try

1. The DOCTYPE, language and charset declaration for HTML5.
- also, title is required
 ```
 The default character encoding in HTML5 is UTF-8.(So, usually omit the second declaration.)
 ```
 ```
<!DOCTYPE html>  
<html lang="en-US">  
<head> 
   <meta charset="UTF-8"> 
   <title>HTML5 Syntax and Coding Style</title>  
</head>  
 ```
2. New HTML5 Elements 
The most interesting new HTML5 elements are:   

New semantic elements like <header>, <footer>, <article>, and <section>.  
New attributes of form elements like number, date, time, calendar, and range.  
New graphic elements: <svg> and <canvas>.  
New multimedia elements: <audio> and <video>. 
   
3. jsut use lower case for elements and attributes! 
   
4. Viewport for all devices
<meta name="viewport" content="width=device-width, initial-scale=1.0">

5. Style Sheets
Use simple syntax for linking to style sheets (the type attribute is not necessary):
```
<link rel="stylesheet" href="styles.css">
```
Only use quotes around values if the value contains spaces

6. Loading JavaScript
Use simple syntax for loading external scripts (the type attribute is not necessary):
```<script src="myscript.js">
```

7. 统计代码
```
正确的cnzz统计代码：

<script type="text/javascript" src='http://s76.cnzz.com/stat.php?id=1033899&amp;web_id=1033899' language='JavaScript' charset='gb2312'></script>
正确的雅虎统计代码：

<script type="text/javascript" src="http://js.tongji.cn.yahoo.com/674708/ystat.js"></script><noscript><a href="http://tongji.cn.yahoo.com"><img alt="" src="http://img.tongji.cn.yahoo.com/674708/ystat.gif"/></a></noscript>
```

8. make Favicon.ico  
[FavIcon from Pics](http://favicon.htmlkit.com/favicon/)

get the favicon, and put it in the root.

```如果您需要将Favicon.ico放到其他目录下，或者希望让不同的网页显示不同的Favicon，那就需要在网页Html文件中做设定了，具体设置也很简单，在Html源代码中的<head>部分加入如下的代码：

<link rel="icon" href="/slyar/favicon.ico" type="image/x-icon">
<link rel="shortcut icon" href="/slyar/favicon.ico" type="image/x-icon">
```
