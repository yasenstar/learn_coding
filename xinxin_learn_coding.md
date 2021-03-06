# XinXin Learn Coding

## 2017/12/16 学习参考与笔记

### Javascript的语法熟悉

#### 准备工作

编写JavaScript脚本不需要任何特殊的软件，一个普通的文本编辑器和一个web浏览器就足够了。
（我们一直使用的Code和SublimeText都是很好的编辑器）

用JavaScript编写的代码必须通过HTML/XHTML文档才能执行。
有两种方法可以做到这点。

第一种方法是将JavaScript代码放到文档<head>标签中的<script>标签之间：

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <title>Example</title>
  <script>
    Javascript goes here...
  </script>
</head>
<body>
  Mark-up goes here...
</body>
</html>
```

一种更好的方法是把JavaScript代码存为一个扩展名为.js的独立文件。
典型的做法是在文档的<head>部分放一个<script>标签，并把它的src属性指向该文件

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <title>Example</title>
  <script src="file.js"></script>
</head>
<body>
  Mark-up goes here...
</body>
</html>
```

但最好的做法是把<script>标签放到HTML文档的最后，</body>标签之前：

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <title>Example</title>
</head>
<body>
  Mark-up goes here...
  <script src="file.js"></script>
</body>
</html>
```

