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





