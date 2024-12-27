📚😎

##### <img src="C:\头像\头像98.jpg"   />

------

---

[TOC]

# 常用

目录:中括号[]+里面输入TOC
新建：Ctrl+N
新建窗口：Ctrl+Shift+N
快速打开：Ctrl+P
另存为：Ctrl+Shift+S
偏好：Ctrl+,
关闭：Ctrl+W
表情符号:win+. (❁´◡`❁)
源代码模式：Ctrl+/
切换全屏：F11
显示隐藏侧边栏：Ctrl+Shift+L
大纲视图：Ctrl+Shift+1
文档列表视图：Ctrl+Shift+2
文件树视图：Ctrl+Shift+3
选中当前行/句：Ctrl+L
开头末尾：ctrl+home/end
查找：Ctrl+F
替换：Ctrl+H
查找下一个：F3<br>查找上一个：Shift+F3
选中当前词：Ctrl+D
跳转到所选内容：Ctrl+J
转移：\+符号
出现错误：ctrl+[

---

# 标题

Ctrl + 123456     //标题
Ctrl +	0		 //普通文本
Ctrl + + -        //对文本的级别加减
//#，＃号与标题间至少一个空格

//# 一级标题

//  <h1>一级标题</h1>>   //转为 html 利用 //h1 ~ h6 tag

//文字下方加任意多 = 表示一级标题

//文字下方加任意多 - 表示二级标题



---

# 段落

这是一行
这是shift+回车

这是 直接回车

--- +回车

---

# 格式

---

## 基础

**加粗：Ctrl+B**

斜体：Ctrl+I*

<u>下划线：Ctrl+U</u>

~~删除线：Alt+Shift+5~~ :~~ ~~
~~wangkk~~

高亮：==wangkk== 

特殊符号 \转移 \*

```markdown
*斜体* _也是斜体_ \*这不是斜体\*
**粗体** __也是粗体__
***粗斜体*** ___也是粗斜体___
`行内代码`
~~删除线~~
<u>下划线</u>
<em>斜体</em>
<strong>粗体</strong>
<code>行内代码</code>
<del>删除线</del>
```

---

## 代码

代码：```+名字+回车

单个代码：` 写`  ``中间写

```tex
w w
```

``` java
public class main()
{
    
}
```

```go
go
```



```python
python
```

` 方法`:``

调用`quick_sort`方法



```c++
#include<iostream>
using namespace std;
int main()
{int a=0;
  return 0;}


```

```tex
WANGKK
```

---

## 放大缩小

实际大小：Ctrl+Shift+0
放大：Ctrl+Shift+=
缩小：Ctrl+Shift±

---

# 插入

---

## 图片

ctrl +shit + i         //图片     align="left" 左右对齐

```c
![图片描述](图片位置)

![](图片位置)

<img src="图片位置" alt="图片描述" 
    style="..."/>
```



<img src="C:\wallpaper\2d8f4c16a7f37cad02ec162d4fd457b41035330202.jpg"   style="width:50%;height:100%;"/>

---

## 数学公式

$$美元里面加数字  //单个公式

ctrl +shift+ M      //公式

行中公式可以用如下方法表示：

- $ 数学公式 $

独立公式可以用如下方法表示：

- $$ 数学公式 $$

---


$$
\sqrt[5]{4x} 开平方\\
\frac{1+y}{5+100t} 除法\\
x^{9100}_{100x}平方下标\\
a^2-b^2=(a+b)*(a-b) 一般写法\\
$$

---

$$
\not= 不等于 \\
\approx 约等于\\
\leq 小于等于\\
\geq 大于等于 \\
\times 乘号\\
\div 除号\\
\pm  正负号\\
\sum 求和符号\\
\prod 累乘\\
\coprod 累除\\
\overline{1+2+3+4=4}
$$

---

$$
90^\circ\\
sinx\\
\sin\\
cosx\\
\cos\\
\sin\pi\\
\arcsin\pi\\
\infty\\
\int\\
\iint\\
\iiiint\\
y\prime\\
\lim\\
\emptyset\\
\in\\
\notin\\
\supset\\
\supseteq\\
\bigcap\\
\bigcup\\
\log\\
\alpha\\
\beta\\
\gamma\\
\delta\\
\eta\\
\omega\\
\theta\\
\sigma\\
\mu\\
\epsilon\\
$$

---

$$
\int_0^1x^2dx\\
\lim_{n\rightarrow+\infty}\frac{1}{n}\\
\sum_1^nx\\
f(x)=\frac{1}{x_1}+\frac{1}{x_2}+\cdots+\frac{1}{x_n}\\
$$



---



## 表格

ctrl +       T        //表格 <br>ctrl+      回车     //插入<br>Tap                   //快速跳到下个单元格<br>shift+ Tap         //往回退<br>ctrl +   shift +delete  //删除行

|      |      |      |
| ---- | ---- | ---- |
|      |      |      |
|      |      |      |
|      |      |      |
|      |      |      |
|      |      |      |

---

## 有序无序列表

Ctrl+Shift+[       //有序列表 数字+.+空格

- 数字加点 后接空格 再接内容
	- 也可以数字加 ) 后接空格 再接内容
- 标准的 md 完全无视数字内容，所有有序列表都从 1 开始计数
- 但一般软件都会处理起始数字
- 有序列表可以和无序列表互相嵌套

```text

```

Ctrl+Shift+]       //无序列表

- `- + *` 后接一个空格然后接内容
- 同一个层级的符号要相同
- 如果一个项中要包含内容，需要换一行然后加一次缩进
- 嵌套列表直接缩进一次即可

``` text
*+空格 -+空格 ++空格
```

​	

Ctrl+Shift+M     //公式块
增加缩进：Ctrl+]  //tap
减少缩进：Ctrl+[  //shift+tap

1. 我是任务
	1. eee

---

## 任务列表

打个无序列表 左边右边不中括号，中间加空格，再空格

``` tex
*+空格 [ ] 
使用 - [ ] 插入未完成任务
使用 - [x] 插入已完成任务
- [ ] task 1 - TODO
- [x] task 2 - DONE
- [ ] task 3 - TODO
    - [ ] task 3.1
    - [x] task 3.2
- comment
```

* [ ] 任务列表




---

## 区块显示(引用):

Ctrl+Shift+Q     //引用
》的的 >+空格

- 一个 > 加一个空格后接内容

- 连续的 > 行属于同一个引言块

- 需要一个空行来退出环境

	

> a a 
>
> d d 
>
> d d 

---

## 超链接

ctrl  +       K       //超链接  ctrl +点击
[名字]+(网站) 

- 方括号 - 圆括号组合
- 文字是要显示的内容，链接附加在其上
- 文字中可以嵌套行内标记格式
- 链接左右加 <> 自动链接

[常用](# 常用：)

[百度一下]()

```te	
[百度一下][a]搜一些东西，去[天猫][b]或者[京东][c]买一些物品
[a]:https://www.baidu.com/
[b]:https://www.tmall.com/
[c]:https://www.jd.com/
```

[百度一下][a]搜一些东西，去[天猫][b]或者[京东][c]买一些物品

[a]:https://www.baidu.com/
[b]:https://www.tmall.com/
[c]:https://www.jd.com/

```markdown
[文字](链接)

<链接>
等价于 [链接](链接)
<a href="链接">文字</a>
```

---

## 脚注  

 这是一个技术[^666]

这是另一种写法[^1]

[^1]: 这是说明 

```tex
[^文本]
[^文本]:解释说明	
```

## 分割线

- 使用 `* - _` 中任意一个字符重复至少三次

- 可以有空格分隔，甚至组织成不同样式

- 被转换为 html 中的 <hr/>

- 分割线上下最好都加空行

- 特别记住 - 分割线上方不要有文字（Setext 标题）

	

## 代码块

- 缩进形式
	- 空行加一个缩进创建一个代码块
	- 内部被原样展现
	- 软件不会进行代码高亮
- 篱笆形式
	- 使用三个或以上 ` 或 ~ 围起来构成代码块
	- ` 或 ~ 后面可以加语言名称
		- 带有高亮支持的软件会对其进行高亮显示
		- 不加（或加 text）不进行高亮

````c
code block:

    print("hello world")
    # line 2

out

```c
#include <stdio.h>

int main() {
    printf("hello world\n");
    return 0;
}
```
````



---

# 视图

​	

~~专注模式：F8~~
打字机模式：F9

打开DevTools：Shift+F12

3.编辑
复制为MarkDown：Ctrl+Shift+C
粘贴为纯文本：Ctrl+Shift+V

选中当前格式文本：Ctrl+E



