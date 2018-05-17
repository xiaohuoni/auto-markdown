# auto-markdown
autocomplete markdown and learn markdown

## md::h1
# title
h1 title,一级标题
## md::h2
## title
h2 title,二级标题
## md::h3
### $1
h3 title,三级标题
## md::h4
#### $1
h4 title (max h6),四级标题(最大支持六级标题)
## md::p 

p paragraph ,段落

## md::cite
> $1
cite ,引用
## md::cite-nesting
> $1
>> $1

nesting cite ,嵌套引用
## md::code-javascript
```js
const a = 1;
console.log(a);
```

## md::code-base
```base
$ npm i oni-cli -g
```
## md::code-html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Document</title>
</head>
<body>
</body>
</html>
```
## md::code-other
```py
if True:
    print "True";
else:
    print "False";
```
Code Block For Other ,代码区域,其他区域，自己写上区域标识
## md::code-in-line
In Line Code like: this is a code `switch` ,行内标记代码，表示出关键字，或者去掉`markdown`的关键字。
## md::italic
*Italic* ,*斜体*
## md::bold
**bold** ,**粗体**
## md::list-・
- Disordered list 
- 无序列表
## md::list-⒈
1. Ordered list 
2. 有序列表
## md::line
*************
Segmenting line ,风格线
## md::link
[Github](https://github.com/xiaohuoni)
link ,链接
## md::image
![Github](https://github.com/account)

Image ,图片，比链接多了一个！号"
## md::copy-right
&copy;
copy right© ,版权符号©
## md::router
[Goto Top](#auto-markdown)
index(router) like `<a href=''></a>` ,索引，类似a标签的跳转
## md::table-explain
| Name | Age | score |
| :- | :-: | -: |
| :- | :-: | -: |
| Chen | 20| 90 |
| Huang | 18 | 100 |
| Zhang  | 17 | 90 |
| text-align: left  | center | right |
| 左对齐  | 居中 | 右对齐 |
