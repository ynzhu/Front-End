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

9. Google Map
```
<!DOCTYPE html>
<html>
<body>

<h1>My First Google Map</h1>

<div id="map" style="width:400px;height:400px;background:yellow"></div>

<script>
function myMap() {
var mapOptions = {
    center: new google.maps.LatLng(51.5, -0.12),
    zoom: 10,
    mapTypeId: google.maps.MapTypeId.HYBRID
}
var map = new google.maps.Map(document.getElementById("map"), mapOptions);
}
</script>

<script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyBu-916DdpKAjTmJNIgngS6HL_kDIKU0aU&callback=myMap"></script>
<!--
To use this code on your website, get a free API key from Google.
Read more at: https://www.w3schools.com/graphics/google_maps_basic.asp
-->

</body>
</html>
```

10. show a video（mp4 mostly)
show a video in HTML, use the <video> element: 
 ```
 <video width="320" height="240" controls, autoplay>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
  Your browser does not support the video tag.
</video>
 ```
 The autoplay attribute does not work in mobile devices like iPad and iPhone.
 
 11. Playing a YouTube Video in HTML
 
To play your video on a web page, do the following:
```
Upload the video to YouTube
Take a note of the video id
Define an <iframe> element in your web page
Let the src attribute point to the video URL
Use the width and height attributes to specify the dimension of the player
Add any other parameters to the URL (see below)
```
```
<iframe width="420" height="315"
src="https://www.youtube.com/embed/XGSy3_Czz8k">
</iframe>
```

12. add icon
```
<!DOCTYPE html>
<html>
<head>
<title>Font Awesome Icons</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
</head>
<body>

<p>Some Font Awesome icons:</p>
<i class="fa fa-cloud"></i>
<i class="fa fa-heart"></i>
<i class="fa fa-car"></i>
<i class="fa fa-file"></i>
<i class="fa fa-bars"></i>

<p>Styled Font Awesome icons (size and color):</p>
<i class="fa fa-cloud" style="font-size:24px;"></i>
<i class="fa fa-cloud" style="font-size:36px;"></i>
<i class="fa fa-cloud" style="font-size:48px;color:red;"></i>
<i class="fa fa-cloud" style="font-size:60px;color:lightblue;"></i>

</body>
</html>
```
