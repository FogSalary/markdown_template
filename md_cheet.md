

# 标题语法
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

<h1> 一级标题 </h1>
<h2> 二级标题 </h2>
<h3> 三级标题 </h3>
<h4> 四级标题 </h4>
<h5> 五级标题 </h5>
<h6> 六级标题 </h6>
<h7> 七级标题 </h7>

一级标题
===============

二级标题
---------------


# 段落语法
I really like using Markdown.

I think I'll use it to format all of my documents from now on.

<p>I really like using Markdown.</p>

<p>I think I'll use it to format all of my documents from now on.</p>


# 换行语法




# 强调语法

### 粗体
I just love **bold text**.

I just love __bold text__.

Love**is**bold

I just love <strong>bold text</strong>.	

I just love <strong>bold text</strong>.

Love<strong>is</strong>bold

### 斜体
Italicized text is the *cat's meow*.

Italicized text is the _cat's meow_.

A*cat*meow

Italicized text is the <em>cat's meow</em>.

Italicized text is the <em>cat's meow</em>.

A<em>cat</em>meow

# 引用语法

> Dorothy followed her through many of the beautiful rooms in her castle.

### 多个段落的块引用
> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

### 嵌套块的引用
> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

### 带有其它元素的块引用
> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.

# 列表语法
### 有序列表

:|
1. First item
2. Second item
3. Third item
4. Fourth item

？

1. First item
1. Second item
1. Third item
1. Fourth item

？

1. First item
8. Second item
3. Third item
5. Fourth item

？

1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item

<ol>
<li>First item</li>
<li>Second item</li>
<li>Third item</li>
<li>Fourth item</li>
</ol>

<ol>
<li>First item</li>
<li>Second item</li>
<li>Third item
<ol>
<li>Indented item</li>
<li>Indented item</li>
</ol>
</li>
<li>Fourth item</li>
</ol>

### 无序列表

- First item
- Second item
- Third item
- Fourth item

？

* First item
* Second item
* Third item
* Fourth item

？

+ First item
+ Second item
+ Third item
+ Fourth item

？

- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item

<ul>
<li>First item</li>
<li>Second item</li>
<li>Third item</li>
<li>Fourth item</li>
</ul>

<ul>
<li>First item</li>
<li>Second item</li>
<li>Third item
<ul>
<li>Indented item</li>
<li>Indented item</li>
</ul>
</li>
<li>Fourth item</li>
</ul>

### 在列表中嵌套其他元素
段落
*   This is the first list item.
*   Here's the second list item.

    I need to add another paragraph below the second list item.

*   And here's the third list item.

引用块
*   This is the first list item.
*   Here's the second list item.

    > A blockquote would look great below the second list item.

*   And here's the third list item.

代码块
1.  Open the file.
2.  Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3.  Update the title to match the name of your website.

图片
1.  Open the file containing the Linux mascot.
2.  Marvel at its beauty.

    ![Tux, the Linux mascot](./img_demo.png)

3.  Close the file.

列表
1. First item
2. Second item
3. Third item
    - Indented item
    - Indented item
4. Fourth item  



# 代码语法

At the command prompt, type `nano`.

At the command prompt, type <code>nano</code>.

# Markdown 围栏代码块
```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### 语法高亮
许多Markdown处理器都支持受围栏代码块的语法突出显示。使用此功能，您可以为编写代码的任何语言添加颜色突出显示。要添加语法突出显示，请在受防护的代码块之前的反引号旁边指定一种语言。
```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### 转义反引号

``Use `code` in your Markdown file.``

<code>Use `code` in your Markdown file.</code>

### 代码块
    <html>
      <head>
      </head>
    </html>


# 分割线语法
***

---

___



# 链接语法
## 给链接增加 Title
[超链接显示名](超链接地址 "超链接 title")

<a href="超链接地址" title="超链接 title">超链接显示名</a>

这是一个链接 [Markdown语法](https://markdown.com.cn "最好的markdown教程")。

## 网址和 Email 地址
<https://markdown.com.cn>

<fake@example.com>

## 带格式化的链接
I love supporting the **[EFF](https://eff.org)**.

This is the *[Markdown Guide](https://www.markdownguide.org)*.

See the section on [`code`](#code).

## 引用类型链接
[hobbit-hole][1]
[hobbit-hole] [1]

# 图片语法
<a href=""><div align=center><img src="img_demo.png" alt="demo" border="0" width="500"/></div></a>


# 转义字符语法

\* Without the backslash, this would be a bullet in an unordered list.

可做转义的字符
\\
\`
\*
\_
\{}
\[]
\()
\#
\+
\-
\.
\!
\|

### 特殊字符自动转义


# 内嵌 HTML 标签

### 行级内联标签
HTML 的行级內联标签如 `<span>、<cite>、<del>` 不受限制，可以在 Markdown 的段落、列表或是标题里任意使用。
HTML 行级內联标签和区块标签不同，在內联标签的范围内， Markdown 的语法是可以解析的。

This **word** is bold. This <em>word</em> is italic.

### 区块标签
区块元素──比如 `<div>、<table>、<pre>、<p>` 等标签，必须在前后加上空行，以便于内容区分。而且这些元素的开始与结尾标签，不可以用 tab 或是空白来缩进。Markdown 会自动识别这区块元素，避免在区块标签前后加上没有必要的 `<p>` 标签。

This is a regular paragraph.

<table>
    <tr>
        <td>Foo</td>
    </tr>
</table>

This is another regular paragraph.


# Markdown 表格

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

单元格宽度可以变化，如下所示。呈现的输出将看起来相同。
| Syntax | Description |
| --- | ----------- |
| Header | Title |
| Paragraph | Text |

### 对齐
您可以通过在标题行中的连字符的左侧，右侧或两侧添加冒号（:），将列中的文本对齐到左侧，右侧或中心。
| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |

### 格式化表格中的文字
您可以在表格中设置文本格式。例如，您可以添加链接，代码（仅反引号（`）中的单词或短语，而不是代码块）和强调。

您不能添加标题，块引用，列表，水平规则，图像或HTML标签。

### 在表中转义管道字符
您可以使用表格的HTML字符代码（&#124;）在表中显示竖线（|）字符。


# Markdown 脚注
脚注使您可以添加注释和参考，而不会使文档正文混乱。当您创建脚注时，带有脚注的上标数字会出现在您添加脚注参考的位置。读者可以单击链接以跳至页面底部的脚注内容。

要创建脚注参考，请在方括号（[^1]）内添加插入符号和标识符。标识符可以是数字或单词，但不能包含空格或制表符。标识符仅将脚注参考与脚注本身相关联-在输出中，脚注按顺序编号。

在括号内使用另一个插入符号和数字添加脚注，并用冒号和文本（[^1]: My footnote.）。您不必在文档末尾添加脚注。您可以将它们放在除列表，块引号和表之类的其他元素之外的任何位置。

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.


# Markdown 标题编号
许多Markdown处理器支持标题的自定义ID - 一些Markdown处理器会自动添加它们。添加自定义ID允许您直接链接到标题并使用CSS对其进行修改。要添加自定义标题ID，请在与标题相同的行上用大括号括起该自定义ID。

### My Great Heading {#custom-id}

<h3 id="custom-id">My Great Heading</h3>

### 链接到标题 ID （#headid）
通过创建带有数字符号（#）和自定义标题ID的[标准链接]((/basic-syntax/links.html)，可以链接到文件中具有自定义ID的标题。

[Heading IDs](#heading-ids)

<a href="#heading-ids">Heading IDs</a>

其他网站可以通过将自定义标题ID添加到网页的完整URL（例如[Heading IDs](https://markdown.com.cn/extended-syntax/heading-ids.html#headid)）来链接到标题。





# Reference:
[Mardown 官方教程](https://markdown.com.cn/basic-syntax/line-breaks.html)
https://www.limfx.pro/ReadArticle/57/yi-zhong-xie-zuo-de-xin-fang-fa
https://github.com/Sakiyary/Markdown-Typora-VSCode-Doc

[Markdown generator tools](https://www.tablesgenerator.com/markdown_tables "tools")

# code


<!-- [1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles" -->