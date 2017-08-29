## banner-mobile ##
是基于原生js实现的web移动端轮播图

### 效果演示 ###

 ![banner](https://coding.net/u/tfx919/p/server/git/raw/master/img/library/banner-mobile/banner.gif)

### 集成步骤 ###
1. 编写html代码，代码结构如下，注意id不能改，图片名字和地址随意即可
```html
<div id="banner-wrap">
    <ul id="banner-list">
        <li><img src="img/banner1.jpg"/></li>
        <li><img src="img/banner2.jpg"/></li>
        <li><img src="img/banner3.jpg"/></li>
    </ul>
</div>
```
2. 在html代码中引入banner.css和banner.js文件
```html
<link rel="stylesheet" href="css/banner.css">
<script type="text/javascript" src="js/banner.js"></script>
```
