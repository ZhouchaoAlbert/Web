W3school内容总结
这里主要针对html学习

一.Html骨架
<!DOCTYPE html>
<head>  
  <title>Document</title>
  <meta charset="UTF-8" />
  <link  .../>
</head>
<body>
</body>
主要由head和body组成，在向其中增加其他元素标签

二.Html常用标签
1.标题标签 (Heading) 
tag: h1 h2 h3 h4 h5 h6
attribute:align对齐
<H1>Hello，Heading</H1>
2.段落标签 (Paragraph) 
tag: p
<p>Hello,Paragraph</p>
3.链接标签 
tag: a
attribute: href
<a href="http://www.baidu.com" >Open Baidu</a>
4.图像标签 
tag: img
attribute: src width height
<img src="https://i1.mifile.cn/f/i/2019/redmi7/sec1.jpg" />

其他标签:
换行标签
tag:br
水平线标签
tag:hr
定义图像地图
tag:map	
定义图像地图中的可点击区域
tag:area
表格
tag:table
    <table>
    <caption></caption>
    <tr>
        <th></th>
    </tr>
    <tr>
        <td></td>
    </tr>
    </table>

三.HTML样式 
style 属性:
background-color 背景颜色
font-family      字体
color            颜色
font-size        字体大小
text-align       文本对齐
text-decoration  无下划线文本
分类：
外部样式表：
tag：link
attribute：rel="stylesheet" type="text/css" href="..."
内部样式表：
<head>
    <style type="text/css">
        body {background-color: red}
        p {margin-left: 20px}
    </style>
</head>
内联样式：
<标签 style="...">


四.HTML 计算机代码
键盘格式
kbd
样式格式
samp
代码格式
code
变量格式化
var
定义预格式化文本
pre

