## Part01 - HTML 和 CSS 的关系 ##
#### 学习 web 前端开发基础技术需要掌握：`HTML`、`CSS`、`JavaScript` 语言。 ####
1. HTML 是网页内容（文字、图片、视频等）的载体。
2. CSS 样式是表现 —— 用来改变内容外观的东西。
3. JavaScript 是用来实现网页上的特效效果。

## Part02 - HTML ##
#### HTML 文件基本结构 ####
> 一个 HTML 文件是有自己固定的结构的。
```html
<html>
  <head>...</head>
  <body>...</body>
</html>
```
1. `<html></html>` 称为根标签，所有的网页标签都在 `<html></html>` 中。
2. `<head>` 标签用于定义文档的头部，是所有头部元素的容器。头部元素有 `<title>`、`<script>`、`<style>`、`<link>`、`<meta>` 等标签。
3. 在 `<body>` 和 `</body>` 标签之间的内容是网页的主要内容，会在浏览器中显示出来。如：`<h1>`、`<p>`、`<a>`、`<img>` 等网页内容标签。
#### HTML 标签 ####
| 标签名                  | 说明                          |
|:---------------------- |:----------------------------- |
| `<html></html>`        | 根标签，所有的网页标签都在其中。 |
| `<head></head>`        | 文档的头部，描述了文档的各种属性和信息。是所有头部元素的容器：`<meta>`、`<title>`、`<link>`、`<style>`、`<script>`。<br>_绝大多数文档头部包含的数据都不会真正作为内容显示给读者。_ |
| `<meta></meta>`        |  |
| `<title></title>`      | 网页的标题信息，用于告诉用户和搜索引擎这个网页的主要内容是什么。搜索引擎可以通过网页标题迅速地判断出网页的主题。<br>_它会出现在浏览器的标题栏中。_ |
| `<link></link>`        |  |
| `<style></style>`      |  |
| `<script></script>`    |  |
| `<body></body>`        |  |
| `<h1></h1>`            | 标题标签 |
| `<p></p>`              | 段落标签 |
| `<a></a>`              |  |
| `<img>`                |  |
> 网页中每一个内容在浏览器中的显示，都要存放到各种标签中。
#### 标签的语法 ####
1. 标签由英文尖括号 `<` 和 `>` 括起来。如：`<html>` 就是一个标签。
2. HTML 中的标签一般都是成对出现的，分 **开始标签** 和 **结束标签** 。结束标签比开始标签多了一个 `/`。如：`<p></p>`。
3. 标签与标签之间是可以嵌套的，但先后顺序必须保持一致。如：`<div>` 里嵌套 `<p>`，那么 `</p>` 必须放在 `</div>` 的前面。
4. HTML 标签不区分大小写，但建议小写。如：`<h1>` 和 `<H1>` 是一样的。

## Part03 - CSS ##

## Part04 小结 ##
以上内容整理自 [HTML+CSS基础课程](http://www.imooc.com/learn/9 'HTML+CSS基础课程')
