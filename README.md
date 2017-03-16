# Autoscroll

## 介绍：
自动向上滚动插件...
基于原生JS编写的代码，轻便，好用;
效果展示(移动端):https://humyfred.github.io/autoscroll/

## 使用：

### 1.列表加上id名：
```html
<div id="autoscroll">
     <div><a href="">1</a></div>
     <div><a href="">2</a></div>
     <div><a href="">3</a></div>
     <div><a href="">4</a></div>
     <div><a href="">5</a></div>
     <div><a href="">7</a></div>
     <div><a href="">8</a></div>
</div>
```
### 2.用div标签包裹该列表：
```html
<div>
     <div id="autoscroll">
          <div><a href="">1</a></div>
          <div><a href="">2</a></div>
          <div><a href="">3</a></div>
          <div><a href="">4</a></div>
          <div><a href="">5</a></div>
          <div><a href="">7</a></div>
          <div><a href="">8</a></div>
     </div>
</div>
```
### 3.引入autoscroll.js之后，在其后加一条js语句：
```html
    <script>
    
      var a = new Autoscroll({
          scrollId:'autoscroll',
          scrollIndex:0,
          fixHeight:'200px',
          stopable:true,
          speed:10
     });

   </script>
```   

### 4.属性配置解说：
scrollId：列表容器的id，

scrollIndex: 列表容器在父亲元素的元素位置(不是节点位置)，如果父亲元素内只有列表容器则可忽略该属性,

fixHeight:列表容器的父亲元素的高度，

stopable：当鼠标移动到列表容器之上是否停止，

speed：  滚动速度；

## 结语：
若网友发现代码有bug或者有好的建议可以发邮件给我，谢谢！！

## License：
This content is released under the MIT License.






