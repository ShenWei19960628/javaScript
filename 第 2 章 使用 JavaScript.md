
# 第 2 章 使用 JavaScript


#### 1.创建一张 HTML 页面

#### 2.<Script>标签解析

#### 3.JS 代码嵌入的一些问题

### 一．创建一张 HTML 页面

##### 虽然现在很多教材开始使用 html5 来讲解 JavaScript 课程。但我认为这样可能比较超前，对于 JavaScript 初学者，我们还是用比较普及和稳定的 xhtml1.x 来创建一张页面。
##### 很多时候，你无法记住 xhtml1.x 过渡性的标准格式。这个时候，建议打开 Dreamweaver 来获取。页面创建好后，编写一个最简单的 JavaScript 脚本（简称 JS 脚本）。
##### 注意网页的编码格式及文件存储的编码。

### 二．<Script>标签解析

##### <script>xxx</script>这组标签，是用于在 html 页面中插入 js 的主要方法。它主要有以下几个属性：

##### 1.charset：可选。表示通过 src 属性指定的字符集。由于大多数浏览器忽略它，所以很少有人用它。

##### 2.defer：可选。表示脚本可以延迟到文档完全被解析和显示之后再执行。由于大多数浏览器不支持，故很少用。

##### 3.language：已废弃。原来用于代码使用的脚本语言。由于大多数浏览器忽略它，所以不要用了。

##### 4.src：可选。表示包含要执行代码的外部文件。

##### 5.type：必需。可以看作是 language 的替代品。表示代码使用的脚本语言的内容类型。范例：type="text/javascript"。

```
<script type="text/javascript">
    alert('欢迎来到 JavaScript 世界！');
</script>
```


### 三．JS 代码嵌入的一些问题

##### 如果你想弹出一个</script>标签的字符串，那么浏览器会误解成 JS 代码已经结束了。解决的方法，就是把字符串分成两个部分，通过连接符‘+’来连接。



```
<script type="text/javascript">

    alert('</scr'+'ipt>');

</script>
```


##### 一般来说，JS 代码越来越庞大的时候，我们最好把他另存为一个.js 文件，通过 src 引入即可。它还具有维护性高、可缓存(加载一次，无需加载)、方便未来扩展的特点。

```
<script type="text/javascript" src="demo1.js"></script>
```
##### 这样标签内就没有任何JS代码了。但，要注意的是，虽然没有任何代码，也不能用单标签：


```
<script type="text/javascript" src="demo1.js" />；
```


##### 也不能在里面添加任何代码：


```
<script type="text/javascript" src="demo1.js">alert('我很可怜，执行不到！')</script>
```


##### 按照常规，我们会把<script>标签存放到<head>...</head>之间。但有时也会放在 body 之间。

##### 不再需要提供注释，以前为了让不支持 JavaScript 浏览器能够屏蔽掉<script>内部的代码，我们习惯在代码的前后用 html 注释掉，现在已经不需要了。

```
<script type="text/javascript"> <!--
alert('欢迎！');

--> </script>
```

##### 平稳退化不支持 JavaScript 处理：<nosciprt>

```
<noscript> 您没有启用 JavaScript</noscript>
```





