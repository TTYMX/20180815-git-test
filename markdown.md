# 语法
### 标题
一个＃表示一级标题，六个＃表示六级标题，没有七级标题
### 无序列表
无序列表有三种表达方式，分别是＊，＋，－，建议使用＊

#### 例子
* 1
* 2
* 3

###有序列表
有序列表只有一种表达方式,并且随着第一个出现的数字递增

####例子
1. eq1
2. eq2
3. eq3

###区块引用
比如说，你想对某个部分做的内容做一些说明或者引用某某的话等，可以使用这个语句

* 不以结婚为目的的谈恋爱都叫耍流氓
>这不是鲁迅说的

* 为中华之崛起而读书
>周恩来

>#### 标题
> * 一级引用
>> * 二级引用
>> * 二级引用
>>> * 三的引用
> * 一级引用
> * 一级引用

### 分割线
分割线可以由*, -, _(星号,减号,底线)表示,但是至少要三个,连续或者不连续都可以,推荐使用减号

####举例
1. ***
2. ---
3. ___

###链接(行内式和参数式)
```
* 这个是行内式[妙语连珠](http://www.baidu.com)是什么意思
[name]:http://www.baidu.com "名称"
* 这个是参数式[name],可以多个[name]
```
* 这个是行内式[妙语连珠](http://www.baidu.com)是什么意思
[name]:http://www.baidu.com "名称"
* 这个是参数式[name],可以多个[name]

* 参数式适用于多个相同链接的场景


###图片 (行内式和参数式)
```
* 这个是百度的图片![图片](http:////www.baidu.com/img/bd_logo1.png?where=super)
[百度图片]:http:////www.baidu.com/img/bd_logo1.png?where=super
* 参数图片,![百度图片]
```
* 比上面的多个!在前面
* 这个是百度的图片![图片](http:////www.baidu.com/img/bd_logo1.png?where=super)
[百度图片]:http:////www.baidu.com/img/bd_logo1.png?where=super
* 参数图片,![百度图片]

###代码框

####单行用两个(反引号)

`<p><a href="homt">门前大桥下</a></p>`

####多行用三个`(反引号)

```
<p><a href="homt">门前大桥下</a></p>
<p><a href="homt">门前大桥下</a></p>
<p><a href="homt">门前大桥下</a></p>
```


###表格
学号|姓名|分数
-|-|-|
1|小明|100

###强调

* 两边跟*表示  *字体倾斜*
* 两边跟_表示  _字体倾斜_ 
* 两边跟**表示 **字体加粗**
* 两边跟__表示 __字体加粗__
* 两边跟两个~表示 ~~字体删除~~
* 转义使用\ 如后面的字符前面都用\<br>
  \\ \* \~
  
  
###字体颜色
* <font face="黑体">我是黑体字</font>
* <font face="微软雅黑">我是微软雅黑</font>
* <font face="STCAIYUN">我是华文彩云</font>
* <font color=#0099ff size=7 face="黑体">color=#0099ff size=72 face="黑体"</font>
* <font color=#00ffff size=72>color=#00ffff</font>
* <font color=gray size=72>color=gray</font>
