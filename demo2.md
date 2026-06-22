# Demo2

## 一、链接demo

### 内嵌式链接

- 外部链接：[百度](http://www.baidu.com)
- 内部链接1，链接 仓库的其他文件：[demo1](demo1.md)
- 内部链接2，链接本文档的其他部分：[代码块demo](demo2.md#代码块-demo)

### 引用式链接

- 外部链接：[百度]
- 外部链接：[百度][baidu]         <!--别名 -->
- 内部链接1，链接 仓库的其他文件：[demo1]
- 内部链接2，链接本文档的其他部分：[代码块demo]

## 二、图片demo

### 图片的内嵌式链接

  ![alt](url text)           <!-- alt跟text为缺省，可略-->
- 外部图片demo
![baidu](https://www.baidu.com/img/PCtm_d9c8750bed0b3c7d089fa7d55720d6cf.png "百度网站")
- 仓库内的图片demo
![](images/open.jfif)

### 图片的引用式链接

- 外部图片demo
![][baidu_logo]
- 仓库内的图片demo
![][open.jfif]


## 三、引用demo

> 这是一个引文。  

出自《出处》

- 多次引用。
>>> 这是多重引文。

## 四、代码块 demo

- 行内代码

这个代码中用来声明变量是`var a = 10`，打印变量内容是`console.log`函数的调用。

- 块式代码

```javascript
var a = 10;
console.log(a);
```



    var a = 10;  
    console.log(a);



<!-- 下面是本文档中用到的链接 -->

[百度]:http://www.baidu.com
[baidu]:http://www.baidu.com
[demo1]:demo1.md
[代码块demo]:demo2.md#代码块-demo

[baidu_logo]:https://www.baidu.com/img/PCtm_d9c8750bed0b3c7d089fa7d55720d6cf.png
[open.jfif]:images/open.jfif
