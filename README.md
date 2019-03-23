# Markdown学习笔记

markdown有官方的初始语法  
但并没有统一标准的语法  
各个渲染器都有各个渲染器所应用的markdown语法，总是有细微的差别，  
但都是多个字符少个字符的差别  
总体上都是差不多的，都基于官方的初始语法而衍生出来

当使用不同的渲染器时  
各种写法试一下，读读语法手册  
哪怕是用不同的编辑器，使用不同的语法，也能写出一样的效果  
多写写就习惯了  
markdown说是轻量级的纯文本标记语言  
其实简单至极，这点语法也就是编译型或解释型编程语言的九牛一毛吧

说到底，markdown还是更注重内容和便捷  
我最开始认真的学习markdown也是因为github网站用它作为readme文档的格式  
虽然我最开始得知markdown这个东西可能是在刷知乎的时候


---

# 0、分割线

第1种分割线表达方式：

>\---

效果如下：

---

第2种分割线表达方式：

>\***

效果如下：

***

---

# 1、标题
(最多6级)

# 1级标题
## 2级标题
### 3级标题
#### 4级标题
##### 5级标题
###### 6级标题

---

# 2、有序列

1. 这是第1个list项
2. 这是第2个list项
3. 这是第3个list项

---

# 3、无序列

第1种无序列表达方式：星号加空格
* 1
    * 1
        * 1
            * 1 这是同一个list项中的第1个段落
                这是同一个list项中的第2个段落
                这是同一个list项中的第3个段落
* 2
* 3

第2种无序列表达方式：加号加空格
+ 1
    + 1
        + 1
            + 1
+ 2
+ 3

第3种无序列表达方式：减号加空格
- 1
    - 1
        - 1
            - 1
- 2
- 3

---

# 4、引用

>春江潮水连海平，海上明月共潮生。  
滟滟随波千万里，何处春江无月明！  
江流宛转绕芳甸，月照花林皆似霰；  
空里流霜不觉飞，汀上白沙看不见。  
江天一色无纤尘，皎皎空中孤月轮。  
江畔何人初见月？江月何年初照人？  
人生代代无穷已，江月年年只相似。  
不知江月待何人，但见长江送流水。  
白云一片去悠悠，青枫浦上不胜愁。  
谁家今夜扁舟子？何处相思明月楼？  
可怜楼上月徘徊，应照离人妆镜台。  
玉户帘中卷不去，捣衣砧上拂还来。  
此时相望不相闻，愿逐月华流照君。  
鸿雁长飞光不度，鱼龙潜跃水成文。  
昨夜闲潭梦落花，可怜春半不还家。  
江水流春去欲尽，江潭落月复西斜。  
斜月沉沉藏海雾，碣石潇湘无限路。  
不知乘月几人归，落月摇情满江树。  

——引用自《春江花月夜》

---

# 5、区块
（1个table键，或者，4个空格键）

    山居秋暝
    （王维）

    空山新雨后，天气晚来秋。
    明月松间照，清泉石上流。
    竹喧归浣女，莲动下渔舟。
    随意春芳歇，王孙自可留。

---

# 6、行内区块

比如说突然来一句诗`却道天凉好个秋`

---

# 7、代码高亮区块

```python
#例如这是一个python代码的代码块
from bs4 import BeautifulSoup
```


---

# 8、插入链接
（链接可以是局域网路径也可以是互联网路径）
（链接可以是相对路径也可以是绝对路径）

第1种插入链接的表达方式
[DenathN的GitHub主页](https://github.com/DenathN "id可写可不写")

第2种插入链接的表达方式
[Google][1] 
[Google][2]
[Google][ggg]
[DenathN的GitHub主页][3]
[DenathN的GitHub主页][4]
[DenathN的GitHub主页][ddd]  

[1]:http://www.google.com "Google"
[2]:http://www.google.com "id可写可不写"
[ggg]:http://www.google.com "GGG"
[3]:https://github.com/DenathN "DenathN"
[4]:https://github.com/DenathN "id可写可不写"
[ddd]:https://github.com/DenathN "DDD"

链接的补充内容部分，要和正文之间空一行，当然，链接的补充内容部分内容不会显示出来

---

# 9、插入图片
（链接可以是局域网路径也可以是互联网路径）
（链接可以是相对路径也可以是绝对路径）

第1种插入图片的表达方式
![DenathN的GitHub头像](https://avatars2.githubusercontent.com/u/40689539?s=400&u=22ad43459c953bdd0a873b072231afdb82ca2881&v=4 "id可写可不写")

第2种插入图片的表达方式
![DenathN的GitHub头像][5]

[5]:https://avatars2.githubusercontent.com/u/40689539?s=400&u=22ad43459c953bdd0a873b072231afdb82ca2881&v=4 "头像"

统一将链接写在文末的补充内容部分，并且要和正文之间空一行，当然，文末的补充内容不会显示出来

---

# 10、粗体

第1种粗体表达方式
**2个星号包围的是粗体**

第2种粗体表达方式
__2个下划线包围的是粗体__

---

# 11、斜体

第1种斜体表达方式
*1个星号包围的是粗体*

第2种斜体表达方式
_1个下划线包围的是粗体_

---

# 12、高亮

==等于符号包围的是高亮的文字==

---

# 13、划掉

~~波浪线符号包围的是划掉的文字~~

---

# 14、下划线

++加法符号包围的是下划线的字体++

---

# 15、表格

|推送人|推送时间|推送安排|
|:-|:-:|-:|
|本列以下内容向左对齐|本列以下内容居中对齐|本列以下内容向右对齐|
|张三|3月1日|干他|
|李四|3月2日|盘他|
|王五|3月3日|杵他|

|        推送人    |    推送时间      |     推送安排     |
|:----------------|:---------------:|----------------:|
|本列以下内容向左对齐|本列以下内容居中对齐|本列以下内容向右对齐|
|张三              |3月1日           |干他              |
|李四              |3月2日           |盘他              |
|王五              |3月3日           |杵他              |

---

# 16、分割线

第1种分割线表达方式：***

***

第2种分割线表达方式：---

---

# 17、分段

隔一行

---

# 18、换行

换行：2个空格+1个回车  
换行：2个空格+1个回车  
换行：2个空格+1个回车  

---

# 19、邮箱地址

<666666666@qq.com>

---

# 20、任务列表

- [ ] 任务1 此任务未做
- [x] 任务2 此任务已做

---

# 21、反斜杠\

相当于反转义作用
使符号成为普通符号，而不会被认为是markdown或者html符号而解析渲染
例如
\>asdasdasd1

---

# 22、注释

第1种注释方式
（markdown原生注释）
[^_^]:
    在中括号里面写个笑脸，冒号，下一行table键之后，再输入注释内容

第2中注释方式
（html原生注释）
<!-- 或者使用html的注释方式，毕竟markdown是被引擎转义为html之后进行显示 -->

---

# 23、markdown显示原理：markdown纯文本是被引擎转义为html代码之后进行显示

所以markdown文本中的html代码，会以html的形式被显示出来

<table>
    <tr>
        <td>这是用原生的HTML代码写的表格</td>
    </tr>
</table>

所以markdown文本中的html代码的标签中的内容，不会被再转义，而是会以html代码的标签中的内容的形式显示出来

<table>
    <tr>
        <td>这是用原生的HTML代码写的表格</td>
    </tr>
    <tr>
        <td>**其中含有markdown语法符号**</td>
    </tr>
    <tr>
        <td>2个星号包围被直接显示</td>
    </tr>
    <tr>
        <td>却并没有被加粗的文字出现</td>
    </tr>
</table>

---


以下待查询：
脚注：[^sample_footnote]

下标（例如化学分子表达式）

上标（例如数学幂表达式）


支持甘特图、流程图，通过将语法写在代码块中，显示图形
