---
　　layout: default
　　title: 你好, markdown
---
##1. 标题设置（让字体变大，和word的标题意思一样）
在**Markdown**当中设置标题，有两种方式：<br/>
第一种：通过在文字下方添加“=”和“-”，他们分别表示一级标题和二级标题。<br/>
第二种：在文字开头加上 “#”，通过“#”数量表示*几级标题*。（一共只有1~6级标题，1级标题字体最大）

##2. 块注释（blockquote）
>     通过在文字开头添加“>”表示块注释。（当>和文字之间添加五个blank时，块注释的文字会有变化。）

* 将需要设置为斜体的文字两端使用1个“*”或者“_”夹起来
* 将需要设置为斜体的文字两端使用2个“*”或者“_”夹起来


This is an [example link](http://example.com/).

I get 10 times more traffic from [Google][1] than from [Yahoo][2] or [MSN][3].

[1]: http://google.com/        "Google" 
[2]: http://search.yahoo.com/  "Yahoo Search" 
[3]: http://search.msn.com/    "MSN Search"

![alt text](/path/to/img.jpg "Title")

![alt text][id]

[id]: /path/to/img.jpg "Title"

`public class static void main(String[] str){
System.out.println("hello world");
}`

	电脑必懂得53个英语单词和缩写 共有 0 条回复件 ... ·PCI：核心装置连接端PeripheralComponent Interconnect ·ATX：指目前电源供给器的规格，也指主机板标准大小尺寸 ·BIOS：硬件(输入/输出)基本设置程序Basic Input Output System ...

hello[^hello]

[^hello]: hi

------------

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
> 
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.


> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
id sem consectetuer libero luctus adipiscing.

> This is the first level of quoting.
>
> > This is nested blockquote.
>
> Back to the first level.


> ## 这是一个标题。
> 
> 1. 这是第一行列表项。
> 2. 这是第二行列表项。
> 
> 给出一些例子代码：
> 
>     return shell_exec("echo $input | $markdown_script");

*   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
    Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
    viverra nec, fringilla in, laoreet vitae, risus.
*   Donec sit amet nisl. Aliquam semper ipsum sit amet velit.
    Suspendisse id sem consectetuer libero luctus adipiscing.
	fdsafsdaf

1.  This is a list item with two paragraphs. Lorem ipsum dolor
    sit amet, consectetuer adipiscing elit. Aliquam hendrerit
    mi posuere lectus.

    Vestibulum enim wisi, viverra nec, fringilla in, laoreet
    vitae, risus. Donec sit amet nisl. Aliquam semper ipsum
    sit amet velit.

2.  Suspendisse id sem consectetuer libero luctus adipiscing.

*   This is a list item with two paragraphs.

    This is the second paragraph in the list item. You're
only required to indent the first line. Lorem ipsum dolor
sit amet, consectetuer adipiscing elit.

*   Another item in the same list.

*   A list item with a blockquote:

    > This is a blockquote
    > inside a list item.

``There is a literal backtick (`) here.``

A single backtick in a code span: `` ` ``

A backtick-delimited string in a code span: `` `foo` ``

<http://example.com/>

\*literal asterisks\*