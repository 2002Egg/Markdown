# RUNOOB Markdown Test
## Hello World!

</br>

# 一.Markdown 标题 
<!-- 通常 用#好标记1-6级标题 1级对应1个# 6级对应6个#-- >
<!-- 注意: 1级标题自带分割线-->

</br>
</br>

# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

</br>

# 二.Markdown段落格式
</br>

## 1.Markdown 段落没有特殊的格式，直接编写文字就好，段落的换行是使用两个以上空格加上回车 或者用 </br>
Runoob</br>runoob



## 2.字体:

*斜体文本*  
_斜体文本_  
**粗体文本**   
__粗体文本__  
***粗斜体文本***   
___粗斜体文本___


</br>

## 3.分割线:
你可以在一行中用三个以上的星号、减号、底线来建立一个分隔线，行内不能有其他东西。你也可以在星号或是减号中间插入空格。下面每种写法都可以建立分隔线：</br>

***

* * *

*****

- - -

------


</br>

## 4.删除线:
如果段落上的文字要添加删除线，只需要在文字的两端加上两个波浪线 ~~ 即可，实例如下：


RUNOOB.COM  
GOOGLE.COM  
~~BAIDU.COM~~


</br>

## 5.下划线:  
下划线可以通过 HTML 的 </u> 标签来实现:  
<u>带下划线文本</u>



</br> 

# 6.脚注: 
脚注是对文本的补充说明  
Markdown 脚注的格式如下:  

[^要注明的文本]  

创建脚注格式类似这样 [^RUNOOB]。  
[^RUNOOB]: 菜鸟教程 -- 学的不仅是技术，更是梦想！！！




</br>

# 三. Markdown列表 
</br>

## 1.Markdown 支持有序列表和无序列表。

无序列表使用星号(*)、加号(+)或是减号(-)作为列表标记，这些标记后面要添加一个空格，然后再填写内容：  
* 第一项
* 第二项
* 第三项

+ 第一项
+ 第二项
+ 第三项


- 第一项
- 第二项
- 第三项

有序列表使用数字并加上 . 号来表示，如：
1. 第一项
2. 第二项
3. 第三项



</br>

## 2. 列表嵌套:  
列表嵌套只需在子列表中的选项前面添加两个或四个空格即可：

1. 第一项：
    * 第一项嵌套的第一个元素
    * 第一项嵌套的第二个元素
2. 第二项：
    * 第二项嵌套的第一个元素
    * 第二项嵌套的第二个元素




</br>

# 四: Markdown区块
</br>

## 1. Markdown 区块引用是在段落开头使用 > 符号 ，然后后面紧跟一个空格符号：  

> 区块引用  
> 菜鸟教程  
> 学的不仅是技术更是梦想

</br>
另外区块是可以嵌套的，一个 > 符号是最外层，两个 > 符号是第一层嵌套，以此类推：

> 最外层
> > 第一层嵌套
> > > 第二层嵌套



</br>

## 2. 区块中使用列表
区块中使用列表实例如下：
> 区块中使用列表
> 1. 第一项
> 2. 第二项
> + 第一项
> + 第二项
> + 第三项



</br>

## 3. 列表中使用区块
如果要在列表项目内放进区块，那么就需要在 > 前添加四个空格的缩进。

列表中使用区块实例如下：
* 第一项
    > RUNOOB  
    > Ha ha
* 第二项
    > Pytorch  
    > > Torch.tensor




</br>

# 五. Markdown代码
</br></br>
如果是段落上的一个函数或片段的代码可以用反引号把它包起来（`），例如：</br>

`printf()` 函数
### 代码区块

代码区块使用 4 个空格或者一个制表符（Tab 键）。</br>

```javascript
$(document).ready(function () {
    alert('RUNOOB');
});
```

</br>

# Markdown 链接
</br>
链接使用方法: </br>
[链接名称](链接地址)

或者

<链接地址>

e.g. 这是一个链接 [菜鸟教程](https://www.runoob.com) </br>
直接使用链接地址：<https://www.runoob.com>
</br>

## 高级链接
我们可以通过变量来设置一个链接，变量赋值在文档末尾进行：

这个链接用 1 作为网址变量 [Google][1]</br>
这个链接用 runoob 作为网址变量 [Runoob][runoob]</br>
然后在文档的结尾为变量赋值（网址）

[1]: http://www.google.com/
[runoob]: http://www.runoob.com/

</br>
</br>

# Markdown 图片
</br>
Markdown 图片语法格式如下：</br>

![alt hah cnm](/Users/liukeyan/Desktop/Software/MarkDown/牛爷爷.jpeg)

![alt 属性文本](/Users/liukeyan/Desktop/Software/MarkDown/图图.jpeg "可选标题")

* 开头一个感叹号 !
* 接着一个方括号，里面放上图片的替代文字
* 接着一个普通括号，里面放上图片的网址，最后还可以用引号包住并加上选择性的 'title' 属性的文字。

e.g. </br>
![RUNOOB 图标](/Users/liukeyan/Desktop/Software/MarkDown/图图.jpeg)

![RUNOOB 图标](/Users/liukeyan/Desktop/Software/MarkDown/牛爷爷.jpeg "RUNOOB")


当然，你也可以像网址那样对图片网址使用变量:</br>
这个链接用 1 作为网址变量 [Google][1]. </br>
然后在文档的结尾为变量赋值（网址）

[1]: http://google.com

这是一个图片链接 [菜鸟图片](http://static.runoob.com/images/runoob-logo.png)

Markdown 还没有办法指定图片的高度与宽度，如果你需要的话，你可以使用普通的 < img > 标签。</br>
<img decoding="async" src="http://static.runoob.com/images/runoob-logo.png" width="50%">


</br>

# Markdown 表格
Markdown 制作表格使用 | 来分隔不同的单元格，使用 - 来分隔表头和其他行。
语法格式如下：

|  表头   | 表头   | 
|  ----  | ----  |
| 单元格  | 单元格 |
| 单元格  | 单元格 |

我们可以设置表格的对齐方式：

* -: 设置内容和标题栏居右对齐。
* :- 设置内容和标题栏居左对齐。
* :-: 设置内容和标题栏居中对齐。

| 左对齐 | 右对齐 | 居中对齐 |
| :-----| ----: | :----: |
| 单元格 | 单元格 | 单元格 |
| 单元格 | 单元格 | 单元格 |

![RUNOOB 图标](/Users/liukeyan/Desktop/Software/MarkDown/table.png)



</br>

# 高级技巧