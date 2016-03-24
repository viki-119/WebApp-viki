# WebApp

移动web最佳的viewport设置  度量viewport= 设备宽度= 布局viewport

     <meta name="viewport" content="width=device-width,initial-scale=1.0,user-scalable=no">
width:设置布局viewport的特定值("device-width")   
initial-scale:设置页面的初始缩放     initial-scale自带width=device-width  
(为了设置使 度量viewport= 布局viewport)  

minimum-scale：最小缩放  
maximum-scale：最大缩放   
user-scalable：用户能否缩放   

布局viewport: document.body.clientWidth

度量viewport: window.innerWidth

在HTML中怎么使页面做出来，不随放大缩小而变形？
http://zhidao.baidu.com/question/1795891798473719907.html?fr=iks&word=user-scalable%3Dno&ie=gbk

PC端:

     <meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, user-scalable=no">

Mobile端:

     <meta name="viewport" content="target-densitydpi=device-dpi, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, user-scalable=no">
