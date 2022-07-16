# Markdown 基本语法

## 标题 {#h-id}

```markdown
# 我是一级标题

## 我是二级标题

### 我是三级标题

#### 四级标题

##### 五级标题

###### 六级标题
```

## 段落

> 要创建段落， 请使用分割一行或多行的文本

我是一个段落

我是真的很喜欢使用 Markdown

## 换行符

> 空格+Enter

这是第一行。  
这是第二行。

##

## 强调加粗

> 2 个星号或下划线

我喜欢**粗字体**。

## 斜体

> 一个星号

_斜体_

## 块引用

> 在段落前加`>`

```markdown
> 我是块引用
```

> 我是块引用

## 带多个段落的块引用

```markdown
> I am kika.
>
> The most beautiful girl in the world!
```

output:

> I am kika.
>
> The most beautiful girl in the world!

## 嵌套引用

```markdown
> I am kika.
>
> > I am kika's friend.
> >
> > > 3
```

output:

> I am kika.
>
> > I am kika's friend.
> >
> > > 3

## 带有其他元素的块引用

> Blockquotes 可以包含 markdown 格式的元素。

```markdown
> #### Markdown learning
>
> - what's Markdown
> - tools
> - basic syntax
>   _EASY_ to use!
```

outpu:

> #### Markdown learning
>
> - what's Markdown
> - tools
> - basic syntax
>
> _EASY_ to use!

## ol list

1. item1
   1. item01
   2. item02
   3. item03
2. item2
3. item3

## ul list

- item1
- item2
- item3

  - item31
  - item32
  - item33

- 1968\. A great year.
- I think 1969 was a great year

## 块引用

- 我是第一个列表项。
- 我是第 2 个列表项。
  > 块引用在第二个列表项
- 我是第 3 个列表项。

## 图片

![img](./public/de-an-sun-NZ4Z5YlBidQ-unsplash.jpg)

## 代码

> `

` <form>`,`<table>`

## 代码块

    <html>
    	<head>
    	</head>
    </html>

```
<html>
	<head>
	</head>
</html>
```

```html
<html>
  <head> </head>
</html>
```

## 水平线

> use \*\*\* or --- or \_\_\_

---

---

---

## link

[arry blog](https://www.arryblog.com/ 'arry')

## url

```markdown
<https://arryblog.com>
<array@163.com>
```

<https://arryblog.com>  
<array@163.com>

## table

```markdown
| 句法      | 描述  | 测试文本 |
| :-------- | :---: | -------: |
| header    | title |  lskflsf |
| paragraph | text  |      ddd |
```

output:
| 句法 | 描述 | 测试文本 |
| :-------- | :---: | -------: |
| header | title | lskflsf |
| paragraph | text | ddd |

## 脚注

这是一个简单的脚注。 [^1] 这也是一个脚注。 [^2]

[^1]: kikakakkakak
[^2]: 11111111

## 标签

```markdown
### i am title {#-id}
```

[title](#标题-h-id)

## 删除线

```markdown
~~ arry is a female. ~~
```

~~ arry is a female. ~~  
== skldkkd ==
