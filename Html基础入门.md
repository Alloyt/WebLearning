---

## HTML基础

##### 如何注释代码



**标签结构**

![一个示范性的代码片断，展示了 html 元素 <p> My cat is very grumpy </p> 的结构。](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started/grumpy-cat-small.png)

1. **开始标签**（Opening tag）：包含元素的名称（本例为 *p*），被左、右角括号所包围。开头标签标志着元素开始或开始生效的地方。
2. **内容**（Content）：元素的内容，本例中就是段落的文本。
3. **结束标签**（Closing tag）：与开始标签相似，只是其在元素名之前包含了一个斜杠。这标志着该元素的结束。

**元素分类**

- **块级元素**：在页面中占一行的元素，任何在它前面或者后面的新元素都出现在新的一行之上，块级元素之间可以互相嵌套，比如列表、标题、段落就是块元素
- **内联元素**: 内联元素之间可以共占一行，通常出现在快级元素中，比如链接、加粗等标签
- **空元素**: 一些没有结束标签的元素叫空元素，比如a标签

**属性**

元素中也可以包含属性，其组成如下

![含有‘class="editor-note"’属性的段落标签](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started/grumpy-cat-attribute-small.png)

- 属性包含一个空格，它处于与元素之间，多个属性需要用空格分开
- 属性名称，属于需要用等号讲值赋值给它
- 属性值，由双引号包裹起来"";

##### HTML基础元素

**如何注释代码**

```
<!-- 注释文字 -->
```
段落标签
```
<p>pass</p>
```
单独设置样式span
```
<span></span>
```
容器标签<div>
```
<div></div>
1. class 样式
2. id 属性
```
框架标签
```
<head></head>
<section>区域标签</section>
<aside>我是侧边栏</ aside>
<footer></footer>
```
换行标签
```html
<br >
```
空格标签
```html
&nbsp;
```
分行标签
```html
<hr />
```
列表
```html
ul->li 圆点列表
ol->li 有序列表
```
图像
```html
<img sr="来源" alt="下载失败描述" title="鼠标悬浮标题">
```
超链接标签
```html
<a href="网址" title=标题 target=是否打开浏览器>文案</a> _self表示当前_blank表示重新打开
```
表格标签
```html
<table border>
caption 表示标题
<tr> 行
<th> 头
<td> 单元格
<thead> 定义表格头部
<tbody> 定义表格内容
<tfoot> 第一页脚
```
用于交互标签
```html
<form method=传输方式 action=交互行为>
<input type="text/password" name="" vale="" >姓名:</input> 文本输入框
</form>
method 表示传输方式post/get
action 表示后端处理程序
type 表示格式，常见有text/password/button/submit
name 表示为文本框命名
value 表示默认值
placeholder 默认占位符
number 表示数字，只允许输入数字
url 网址输入框
email 邮箱
```
**标签对应**

```html
<label for="id">
<input type="text" id="user"> for需要与id对应
```
**选择框***

```html
<input type="radio" value="值" name="名称" checked="checked" /> 
1. radio单选、checkbox 复选
2. value 需要提交的值
3. name 空间的名字
checked="checked" 等于设置默认选择
```

**下拉菜单**

```html
<select></select> 表示开始
<option value="旅游">选项</option> 表示下拉
1. value="" 表示需要提交的值
2. 中间表示选项
3. selected="selected" 表示默认选择的值
```

**提交/重置按钮**

```html
<input type="" value="name" name="myname"/>
1. text 表示输入
2. submit 表示提交
3. value 表示默认的值
4. reset 表示重置
```

