# markdown-test
make
##  学习语法

### 学习段落 标题 代码块

2.1.1 段落

##### 关于标题处理方法 和处理结果 

下面方一个代码块:
>--- 这个方法是给skin模型加入 沟边 
>
> fn skinmode_addbone  none  bonenodes   = (
>
>	max modify mode
>	modefiers_node = undefined  
>	if classof none.modifiers[1]== Skin then (
>		modefiers_node = none.modifiers[1]
>		
>	)
>	if modefiers_node == undefined then (
>		
>		 setListenerSelText("传入模型的修改器，要保证最顶层是 skin ")
>		return false 
>		
>	)
>	
>	 --- 加入必须选择none 
>	 select none 
>	--- 加入骨骼 
>	for i in bonenodes do (
>		skinops.addbone    modefiers_node   i -1 
>		
>	)
>
>)
>)
> 
说明说的过程**有点问题** 主要实现给*skin模型*加入_s_  __骨骼__ 


* 测试
* 测试1

- 测试
- 测试 

+ 测试
+ 测试


有序标记：
1. 测试
2. 测试

测试图标：

#### 学习链接方式 ： 
+ 学习行内链接方式 
***

 【说明】
 该种链接方式其实就是 超链接凡是 

[链接](https://github.com/pyclyy/markdown-test/blob/master/Snipaste_2019-06-13_21-22-31.png)

[链接1](http://baidu.com/)

[链接2](http://163.com/)


> 显示图 要求是jpj的 

![显示出来](https://github.com/pyclyy/markdown-test/blob/master/Snipaste_2019-06-13_21-22-31.png)

还是显示不出来 


### 测试链这种不行
我喜欢的网站有[百度][1]和
[好123][2] or [GitHub][3].
[1]: http://baidu.com/ "baidu"
[2]: http://www.hao123.com/ "好123"
[3]: https://github.com/ "GitHub"
***



[链接] (http://baidu.com/)

制作表格 

**ceshi **
****

+ 1 
+  2
+  4 
+  5

+ ONE 
  + TWO 
    + CC 
    + DD
      + BBB 
      + BB 

 必须加一个 |-|-| 这种形式 

|姓名|所在地|产品|
| -|-|-    |
|雷军|北京 |小米手机|
|老罗|北京|锤子手机|
|任正非|深圳|华为手机|


![](https://github.com/pyclyy/markdown-test/blob/master/Snipaste_2019-06-13_21-22-31.png)

- 有允许插入哦功能  
![61儿童](http://www.astiron.com/data/upload/image/201506/7748386409f3a7206cb4d7dfa24c78ce.jpg)


![](https://github.com/pyclyy/markdown-test/blob/master/Snipaste_2019-06-13_21-22-31.png?raw=true)


+ 利用图片地址形式是可以的 
![](https://github.com/pyclyy/markdown-test/blob/master/Snipaste_2019-06-13_21-31-48.jpg?raw=true)


