README
===========================
感谢你可以看这个文档，不良费时间现在开始介绍。最近要做的事情以及文档的查看方法写在这里。
当前正在做的工作在[Step_and_Current_Question](#step_and_current_question)有记录,如果你打算加入我们可以从当前正在解决的问题开始入手。  
如果你是第一次来不了解这个项目，请查看[就这么简单，我会继续完善说明图片，简单说明这个应用](#description描述)  
我们是中国人，英文如果有问题请帮我修改，谢谢。  

thanks for your see this document,explain about to document now.the work being done at the moment and check document out way is writing here.   
the work at the moment being done is recorded in [Step_and_Current_Question](#step_and_current_question),if would you like join us,you can begin with the problems that being solved at the moment.   
if your see the document first and disunderstand the project.plese check out [description](#description描述).  

we are chinese,if english have incorrected would your please fix it. thank your.   
****
	
|Author|qiulongquan|
|---|---
|E-mail|2215804749@qq.com

## 我要简单一些写明白这个应用（as much as possible easy explain the project）
* [干什么](#干什么)(the project is what)
	* 打开手机端APP 或者 PC端的网页 然后页面上面就出现了你感兴趣的网站内容。（就这么简单，就这一个功能）
	* open the smart phone is APP or open web page on the PC client ,the content of website you interested in appear on the page（so easy,only one function）
* [怎么用](#怎么用)(how usage)
	* 第一次使用会打开一个“内容分类”选项，你可以选择自己感兴趣的内容。然后系统根据你选择的内容从数据库中挑选出其他同类客户也喜欢的内容。然后展现出来。
你喜欢的内容就点击进去浏览，没有喜欢的就选择“换一批”，系统会把下一批内容推荐给你。机器学习会根据你多次点击来学习针对单个客户喜欢的内容。下次打开页面
就会更加精准内容推荐出来。
	* first time use will appear a "content category" option,you can select yourself interest content.then system will by selected contents pick out from database contents that other like user also interested in.then show it.   
click you like contents check it out,not like then click "next" ,system will change new recommend content for you . machine learning will by user multipic clicks learn that individual customers interest in contents . next time open the APP more accurate contents will be recommend.   

* [就这么简单，我会继续完善说明图片，简单说明这个应用](#description描述)   
	so simple,we will be continue to improve the description picture,simple explain the APP
* [Step_and_Current_Question](#step_and_current_question)
* [Install](#install)
* [CLI](#cli)
* [Usage](#usage)
* [Development](#development)
* [Team](#team)
****
## Description描述

![description1](https://github.com/tuijian/tuijian/blob/master/ready_pic/pic1.JPG "description1")
![description2](https://github.com/tuijian/tuijian/blob/master/ready_pic/pic2.JPG "description2")
![description3](https://github.com/tuijian/tuijian/blob/master/ready_pic/pic3.JPG "description3")
![description4](https://github.com/tuijian/tuijian/blob/master/ready_pic/pic4.JPG "description4")
![description5](https://github.com/tuijian/tuijian/blob/master/ready_pic/pic5.JPG "description5")

![description6](https://github.com/tuijian/tuijian/blob/master/ready_pic/pic6.JPG "description6")

****
## Step_and_Current_Question
* 模块机能分割  
```diff
+ 主要机能拆分(main function identify)（doing at the moment）   
* 主要机能包括(main function include)
	* 网络爬虫抓取信息，自动打标签。   
	(web crawler capture information,automatic get website labeling)
	* 设计数据库采用mysql，要稳定 维护简单。   
	(designing database usage MYSQL,stabilization and simple maintenance)
	* 参考成熟的机器学习算法加以利用。尽可能少的次数展现出想要的结果。   
	(reference to mature machine learning algorithm and usage,
	as much as possible little click then appear hope result)

```

* Web Crawler realization ウェブクローラー  
网络小爬虫 找到合适的内容然后自动打标签

* DB設計　導入  
设计一个数据库不要太复杂 存放网站标签 稳定运行就可以

* machine learning algorithm realization アルゴリズム  
这个最难 我还不知道用那个算法实现

* result display   
结果输出   一开始不要界面  算法出来的理论值和实际值能够输出就可以。

* 上面是当前开发中遇到的问题，如果你有好的解决问题方法，请新建一个branch，并提供你的方案。我们会把有你放入贡献者名单中。
****
## Install

****
## CLI

****
## Usage

****
## Development

* [Clone](https://help.github.com/articles/cloning-a-repository/ "Clone URL") this repository to your local machine
* Navigate to your clone cd tuijian

****
## Team
|Author|qiulongquan|
|---|---
|E-mail|2215804749@qq.com

|collaborate|XXXXXXXXX|
|---|---
|E-mail|quickly join us please




|#|语法|效果|
|---|---|----
|1|`![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")`|![baidu](https://github.com/tuijian/tuijian/blob/master/ready_pic/pic1.JPG "description1")
|2|`![][foryou123]`|![][foryou123]

注意例2的写法使用了**URL标识符**的形式，在[链接](#链接)一节有介绍。
>在文末有foryou的定义：
```
[foryou123]:https://github.com/tuijian/tuijian/blob/master/ready_pic/pic1.JPG 



****
##Install
目录
* [横线](#横线)
* [标题](#标题)
* [文本](#文本)
    * 普通文本
    * 单行文本
    * 多行文本
    * 文字高亮
    * 换行
    * 斜体
    * 粗体
    * 删除线
* [图片](#图片)
    * 来源于网络的图片
    * GitHub仓库中的图片
* [链接](#链接) 
    * 文字超链接
        *  链接外部URL
        *  链接本仓库里的URL
    *  锚点
    * [图片链接](#图片链接)
* [列表](#列表)
    * 无序列表
    * 有序列表
    * 复选框列表
* [块引用](#块引用)
* [代码高亮](#代码高亮)
* [表格](#表格) 
* [表情](#表情)
* [diff语法](#diff语法)

#CLI
###CLI
 横线
-----------
***、---、___可以显示横线效果

***
---
___



标题
------

# 一级标题  
## 二级标题  
### 三级标题  
#### 四级标题  
##### 五级标题  
###### 六级标题  


文本
------
### 普通文本
这是一段普通的文本
### 单行文本
    Hello,大家好，我是果冻虾仁。
在一行开头加入1个Tab或者4个空格。
### 文本块
#### 语法1
在连续几行的文本开头加入1个Tab或者4个空格。

    欢迎到访
    很高兴见到您
    祝您，早上好，中午好，下午好，晚安

#### 语法2
使用一对各三个的反引号：
```
欢迎到访
我是C++码农
你可以在知乎、CSDN、简书搜索【果冻虾仁】找到我
```
该语法也可以实现代码高亮，见[代码高亮](#代码高亮)
### 文字高亮
文字高亮功能能使行内部分文字高亮，使用一对反引号。
语法：
```
`linux` `网络编程` `socket` `epoll` 
```
效果：`linux` `网络编程` `socket` `epoll`

也适合做一篇文章的tag
#### 换行
直接回车不能换行，  
可以在上一行文本后面补两个空格，  
这样下一行的文本就换行了。

或者就是在两行文本直接加一个空行。

也能实现换行效果，不过这个行间距有点大。
#### 斜体、粗体、删除线

|语法|效果|
|----|-----|
|`*斜体1*`|*斜体1*|
|`_斜体2_`| _斜体2_|
|`**粗体1**`|**粗体1**|
|`__粗体2__`|__粗体2__|
|`这是一个 ~~删除线~~`|这是一个 ~~删除线~~|
|`***斜粗体1***`|***斜粗体1***|
|`___斜粗体2___`|___斜粗体2___|
|`***~~斜粗体删除线1~~***`|***~~斜粗体删除线1~~***|
|`~~***斜粗体删除线2***~~`|~~***斜粗体删除线2***~~|

    斜体、粗体、删除线可混合使用

图片
------
基本格式：
```
![alt](URL title)
```
alt和title即对应HTML中的alt和title属性（都可省略）：
- alt表示图片显示失败时的替换文本
- title表示鼠标悬停在图片时的显示文本（注意这里要加引号）

URL即图片的url地址，如果引用本仓库中的图片，直接使用**相对路径**就可了，如果引用其他github仓库中的图片要注意格式，即：`仓库地址/raw/分支名/图片路径`，如：
```
https://github.com/guodongxiaren/ImageCache/raw/master/Logo/foryou.gif
```

|#|语法|效果|
|---|---|----
|1|`![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")`|![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")
|2|`![][foryou]`|![][foryou]

注意例2的写法使用了**URL标识符**的形式，在[链接](#链接)一节有介绍。
>在文末有foryou的定义：
```
[foryou]:https://github.com/guodongxiaren/ImageCache/raw/master/Logo/foryou.gif
```

链接
------
### 链接外部URL

|#|语法|效果|
|---|----|-----|
|1|`[我的博客](http://blog.csdn.net/guodongxiaren "悬停显示")`|[我的博客](http://blog.csdn.net/guodongxiaren "悬停显示")|
|2|`[我的知乎][zhihu] `|[我的知乎][zhihu] |

语法2由两部分组成：
- 第一部分使用两个中括号，[ ]里的标识符（本例中zhihu），可以是数字，字母等的组合，标识符上下对应就行了（**姑且称之为URL标识符**）
- 第二部分标记实际URL。

>使用URL标识符能达到复用的目的，一般把全文所有的URL标识符统一放在文章末尾，这样看起来比较干净。
>>URL标识符是我起的名字，不知道是否准确。囧。。

### 链接本仓库里的URL

|语法|效果|
|----|-----|
|`[我的简介](/example/profile.md)`|[我的简介](/example/profile.md)|
|`[Book](./Book)`|[Book](/Book)|

### 图片链接
给图片加链接的本质是混合图片显示语法和普通的链接语法。普通的链接中[ ]内部是链接要显示的文本，而图片链接[ ]里面则是要显示的图片。  
直接混合两种语法当然可以，但是十分啰嗦，为此我们可以使用URL标识符的形式。

|#|语法|效果|
|---|----|:---:|
|1|`[![weibo-logo]](http://weibo.com/linpiaochen)`|[![weibo-logo]](http://weibo.com/linpiaochen)|
|2|`[![](/img/zhihu.png "我的知乎，欢迎关注")][zhihu]`|[![](/img/zhihu.png "我的知乎，欢迎关注")][zhihu]|
|3|`[![csdn-logo]][csdn]`|[![csdn-logo]][csdn]|

因为图片本身和链接本身都支持URL标识符的形式，所以图片链接也可以很简洁（见例3）。  
注意，此时鼠标悬停时显示的文字是图片的title，而非链接本身的title了。
> 本文URL标识符都放置于文末

### 锚点
其实呢，每一个标题都是一个锚点，和HTML的锚点（`#`）类似，比如我们 

|语法|效果|
|---|---|
|`[回到顶部](#readme)`|[回到顶部](#readme)|

不过要注意，标题中的英文字母都被转化为**小写字母**了。
> 以前GitHub对中文支持的不好，所以中文标题不能正确识别为锚点，但是现在已经没问题啦！

## 列表
### 无序列表
* 昵称：果冻虾仁
- 别名：隔壁老王
* 英文名：Jelly

### 多级无序列表
* 编程语言
    * 脚本语言
        * Python

### 有序列表
#### 一般效果
就是在数字后面加一个点，再加一个空格。不过看起来起来可能不够明显。    
面向对象的三个基本特征：

1. 封装
2. 继承
3. 多态


#### 多级有序列表
和无序列表一样，有序列表也有多级结构：  

1. 这是一级的有序列表，数字1还是1
   1. 这是二级的有序列表，阿拉伯数字在显示的时候变成了罗马数字
      1. 这是三级的有序列表，数字在显示的时候变成了英文字母
	 

### 复选框列表
- [x] 需求分析
- [x] 系统设计
- [x] 详细设计
- [ ] 编码
- [ ] 测试
- [ ] 交付

您可以使用这个功能来标注某个项目各项任务的完成情况。
> Tip:
>> 在GitHub的**issue**中使用该语法是可以实时点击复选框来勾选或解除勾选的，而无需修改issue原文。

## 块引用

### 常用于引用文本
#### 文本摘自《深入理解计算机系统》P27
　令人吃惊的是，在哪种字节顺序是合适的这个问题上，人们表现得非常情绪化。实际上术语“little endian”（小端）和“big endian”（大端）出自Jonathan Swift的《格利佛游记》一书，其中交战的两个派别无法就应该从哪一端打开一个半熟的鸡蛋达成一致。因此，争论沦为关于社会政治的争论。只要选择了一种规则并且始终如一的坚持，其实对于哪种字节排序的选择都是任意的。
> **“端”（endian）的起源**  
以下是Jonathan Swift在1726年关于大小端之争历史的描述：  
“……下面我要告诉你的是，Lilliput和Blefuscu这两大强国在过去36个月里一直在苦战。战争开始是由于以下的原因：我们大家都认为，吃鸡蛋前，原始的方法是打破鸡蛋较大的一端，可是当今的皇帝的祖父小时候吃鸡蛋，一次按古法打鸡蛋时碰巧将一个手指弄破了，因此他的父亲，当时的皇帝，就下了一道敕令，命令全体臣民吃鸡蛋时打破较小的一端，违令者重罚。”

### 块引用有多级结构
> 数据结构
>> 树
>>> 二叉树
>>>> 平衡二叉树
>>>>> 满二叉树

代码高亮
----------
在三个反引号后面加上编程语言的名字，另起一行开始写代码，最后一行再加上三个反引号。
```Java
public static void main(String[]args){} //Java
```
```c
int main(int argc, char *argv[]) //C
```
```Bash
echo "hello GitHub" #Bash
```
```javascript
document.getElementById("myH1").innerHTML="Welcome to my Homepage"; //javascipt
```
```cpp
string &operator+(const string& A,const string& B) //cpp
```
表格
--------

表头1  | 表头2|
--------- | --------|
表格单元  | 表格单元 |
表格单元  | 表格单元 |

| 表头1  | 表头2|
| ---------- | -----------|
| 表格单元   | 表格单元   |
| 表格单元   | 表格单元   |

### 对齐
表格可以指定对齐方式

| 左对齐 | 居中  | 右对齐 |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |

### 混合其他语法
表格单元中的内容可以和其他大多数GFM语法配合使用，如：  
#### 使用普通文本的删除线，斜体等效果

| 名字 | 描述 |
| ------------- | ----------- |
| Help      | ~~Display the~~ help window.|
| Close     | _Closes_ a window     |

#### 表格中嵌入图片（链接）
其实前面介绍图片显示、图片链接的时候为了清晰就是放在在表格中显示的。

| 图片 | 描述 |
| ---- | ---- |
|![baidu][baidu-logo] | 百度|

表情
----------
Github的Markdown语法支持添加emoji表情，输入不同的符号码（两个冒号包围的字符）可以显示出不同的表情。

比如`:blush:`，可以显示:blush:。

具体每一个表情的符号码，可以查询GitHub的官方网页[http://www.emoji-cheat-sheet.com](http://www.emoji-cheat-sheet.com)。

但是这个网页每次都打开**奇慢**。。所以我整理到了本repo中，大家可以直接在此查看[emoji](./emoji.md)。

diff语法
---------
版本控制的系统中都少不了diff的功能，即展示一个文件内容的增加与删除。
GFM中可以显示的展示diff效果。使用绿色表示新增，红色表示删除。

其语法与代码高亮类似，只是在三个反引号后面写diff，
并且其内容中，以 `+ `开头表示新增，`- `开头表示删除。

效果如下：

```diff
+ 鸟宿池边树，僧敲月下门
- 鸟宿池边树，僧推月下门
```



--------------------------------
[csdn]:http://blog.csdn.net/guodongxiaren "我的博客"
[zhihu]:https://www.zhihu.com/people/jellywong "我的知乎，欢迎关注"
[weibo]:http://weibo.com/linpiaochen
[baidu-logo]:http://www.baidu.com/img/bdlogo.gif "百度logo"
[weibo-logo]:/img/weibo.png "点击图片进入我的微博"
[csdn-logo]:/img/csdn.png "我的CSDN博客"
[foryou]:https://github.com/guodongxiaren/ImageCache/raw/master/Logo/foryou.gif
