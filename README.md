# web-designerName
移动端web开发   rem布局方式  暑期实践项目

### 项目介绍

* 布局方式采用了rem方式来进行适配

* 根据不同的设备，通过JS来计算html的fontSize

* 本项目纯展示作用,代码写的时候也没有考虑很多

* 当时觉得自己写出来这样的页面觉得很牛了(low)  现在看自己的代码还是不忍直视的 ~~~~

```JS

(function(){
     var html = document.documentElement;
     var width = html.getBoundingClientRect().width;

     html.style.fontSize = width/15+'px';

  })();

```


#### 项目结构  /designerName/

``` sh
├── css/ # css样式目录
├── html/ # 视图目录
├── img/ # 图片资源目录
├── js/ # js脚本目录
├── index.html # 项目首页

```

* 敢于尝试的你 其实已经进步了 ^_^



