# demo2

## 链接

**[方括号里面放链接的文字](圆括号里面放链接的地址)**

### 内嵌式链接
- 外部链接:[百度](https://www.baidu.com)  
- 内部链接1,链接仓库的其他文件:[demo1](demo1.md)
- 内部链接2,链接本文档的其他部分: [代码块demo](demo2.md#代码块 demo)

### 引用式链接
- 外部链接:[百度]  
- 外部链接:[百度][baidu]
- 内部链接1,链接仓库的其他文件:[demo1]
- 内部链接2,链接本文档的其他部分: [代码块demo]

## 图片

加！号代表的是要插入图片 ![方括号相当于img标签里面的alt属性，当图片不显示时会显示图片里面的文字](圆括号里面是我们图片的地址 空格 后面是提示的文字)  
图片的MarkDown语法:  

	**![alt](url text)**

### 图片的内嵌式：  

外部图片 demo:  
![百度](https://www.baidu.com/img/bd_logo1.png "百度一下，你就知道")

内部图片 demo:
![背景图片](image/pic.png "背景图片")


### 图片的引用式链接：

外部图片 demo:  
![百度][baidu_logo]

内部图片 demo:
![pic][pic_png]



## 引用

引用表示引用别人的话，引经据典

引用以一个大于号开始，效果是有一条竖线

> 这是一段引文

——出自《出处》

**多次引用**
>>> 几个大于号表示引用几次


## 代码块

**代码块分为两种：**

- 行内代码：

这个代码中用来声明变量是`var a = 10`,打印变量内容是 `console.log` 函数的调用。

- 块式代码：

```javascript
var a = 10;
var b = 20;
console.log(a + b)
```

	var a = 10;
	var b = 20;
	console.log(a + b)

**这种写法虽然也能生成代码块，但是我们却很少使用，因为它不能指定那个语言**


<!--  下面是本文当中用到的链接  -->
[百度]: https://www.baidu.com
[baidu]: https://www.baidu.com
[demo1]: demo1.md
[代码块demo]: demo2.md#代码块-demo

[pic_png]:image/pic.png "背景图片"
[baidu_logo]:https://www.baidu.com/img/bd_logo1.png "百度一下，你就知道"
