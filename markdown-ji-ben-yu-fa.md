# markdown基本语法

{% hint style="info" %}
 提示:可能有些语法显示的不明显！
{% endhint %}

## 一、标题

语法:

在想要设置为标题的文字前面加`#`来表示

示例:

```text
# 这是一级标题
## 这是二级标题
### 这是三级标题
#### 这是四级标题
##### 这是五级标题
###### 这是六级标题
```

 效果如下:

![](.gitbook/assets/markdown-ji-ben-yu-fa-title.png)

## 二、字体

### 2.1 加粗和倾斜

语法:

要加粗的文字左右分别用两个`*`号包起来  
要倾斜的文字左右分别用一个`*`号包起来  
要倾斜和加粗的文字左右分别用三个`*`号包起来  
要加删除线的文字左右分别用两个`~`号包起来

示例:

```text
*这是倾斜的文字*`
**这是加粗的文字**
***这是斜体加粗的文字***
~~这是加删除线的文字~~
```

 效果如下:

![](.gitbook/assets/markdown-ji-ben-yu-fa-font.png)

### 2.1 颜色、大小、字体类型

语法:

使用`font`标签，

```text
<font face="微软雅黑">我是微软雅黑</font> //设置字体类型 
<font color="#ff0000">我是红色</font>  //设置字体颜色
<font size="72px">我的大小为72px</font>  //设置字体大小
```

 示例:

```text
<font face="微软雅黑">我是微软雅黑</font>  
<font color="#ff0000">我是红色</font>  
<font size="72px">我的大小为72px</font>  
```

##  三、引用

语法:

在引用的文字前加&gt;即可。引用也可以嵌套，如加两个&gt;&gt;三个&gt;&gt;&gt;n个...

示例:

```text
>这是引用的内容
>>这是引用的内容
>>>>>>>>>>这是引用的内容
```

 效果如下:

![](.gitbook/assets/markdown-ji-ben-yu-fa-quote.png)

## 四、分割线

语法:

三个或者三个以上的 - 或者 \* 都可以。

示例:

```text
---
----
***
*****
```

效果如下:

![](.gitbook/assets/markdown-ji-ben-yu-fa-fengexian.png)

## 五、图片

语法:

```text
![图片alt](图片地址 "图片title")

图片alt就是显示在图片下面的文字，相当于对图片内容的解释。
图片title是图片的标题，当鼠标移到图片上时显示的内容。title可加可不加
```

示例:

```text
![图片alt](https://avatars2.githubusercontent.com/u/9973145?s=460&v=4 "图片title")
```

效果如下:

![](.gitbook/assets/markdown-ji-ben-yu-fa-image.png)

## 六、超链接

语法:

```text
[超链接名](超链接地址 "超链接title")
title可加可不加
```

示例:

```text
[GitHub](https://github.com "GitHub")
[百度](http://baidu.com)
```

效果如下:

[GitHub](https://github.com) 

[百度](http://baidu.com)

## 七、列表

