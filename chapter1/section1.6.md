# 1.6 就地解决

能在这个页面解决的问题，就不要去其它页面解决，因为任何页面刷新和跳转都会引起变化盲视（Change Blindness），导致用户心流（Flow）被打断。频繁的页面刷新和跳转，就像在看戏时，演员说完一行台词就安排一次谢幕一样。


> 变换盲视（Change Blindness） ：指视觉场景中的某些变化并未被观察者注意到的心理现象。产生这种现象的原因包括场景中的障碍物，眼球运动、地点的变化，或者是缺乏注意力等。——摘自《维基百科》
>
心流（Flow） ：也有别名以化境 (Zone) 表示，亦有人翻译为神驰状态，定义是一种将个人精神力完全投注在某种活动上的感觉；心流产生时同时会有高度的兴奋及充实感。——摘自《维基百科》


- 覆盖层
- 嵌入层
- 虚拟页面
- 流程处理

### 覆盖层

二次确认覆盖层：避免滥用 Modal 进行二次确认，应该勇敢的让用户去尝试，给用户机会『撤消』即可。

![](https://os.alipayobjects.com/rmsportal/woHOTIZeXCYmtkv.png)推荐示例![right](http://img.hb.aicdn.com/b49d5ad38bcfc1a03cba2b5f576ba413db11d2641d34-E9Mdqo_fw658)

用户点击『删除』后，直接操作；出现 Message 告知用户操作成功，并提供用户『撤消』的按钮；用户进行下一个操作或者 1 分钟内不进行任何操作， Message 消失，用户无法再『撤消』。

![](https://os.alipayobjects.com/rmsportal/JEcWKBYlMcYIowX.png)不推荐示例![error](http://7xtoga.com1.z0.glb.clouddn.com/snipaste20170517_172651.png)

滥用 Modal 进行二次确认，就像『狼来了』一样，既打断用户心流（无法将上下文带到弹出框中），也无法避免失误的发生。
二次确认覆盖层：避免滥用 Modal 进行二次确认，应该勇敢的让用户去尝试，给用户机会『撤消』即可。

![](https://os.alipayobjects.com/rmsportal/hDlhNscVtHdvvgu.png)特殊示例![](http://img.hb.aicdn.com/b49d5ad38bcfc1a03cba2b5f576ba413db11d2641d34-E9Mdqo_fw658)

特例：在执行某些无法『撤消』的操作时，可以点击『删除』后，出现 Popconfirm 进行二次确认，在当前页面完成任务。


----------



**详情覆盖层：一般在列表中，通过用户『悬停』/『点击』某个区块，在当前页加载该条列表项的更多详情信息。**

> 注：使用『悬停』激活时，当鼠标移入时，需要设置 0.5 秒左右的延迟触发；当鼠标移出时，立刻关闭覆盖层

![](https://os.alipayobjects.com/rmsportal/WIhhhXExyQBsZwj.png)

输入覆盖层：在覆盖层上，让用户直接进行少量字段的输入。

![](https://os.alipayobjects.com/rmsportal/YehbrRkldqWsezo.png)
输入覆盖层示例

鼠标『点击』图标触发；鼠标『点击』悬浮层以外的其他区块后，直接保存输入结果并退出。
> 就地解决


----------
### 嵌入层

列表嵌入层：在列表中，显示某条列表项的详情信息，保持上下文不中断。

![](https://os.alipayobjects.com/rmsportal/bHCqDMqXhZvKbve.png)

标签页：将多个平级的信息进行整理和分类了，一次只显示一组信息。

![](https://os.alipayobjects.com/rmsportal/MsVyvEIJtlxZWBL.png)


----------

### 虚拟页面

在交互过程中，『覆盖层』可以在当前页面上方显示附加内容和交互链接；『嵌入层』可以在页面内部实现同样效果；而『虚拟页面』不局限机械时代的『页面』，可以利用信息时代的特点构建一种新型『页面』。

---

### 流程处理

长期以来，Web 实现流程的方式就是把每个步骤放在一个单独的页面上。虽然这种做法是分解问题最简单的方式，但并不是最佳解决方案。对于某些『流程处理』而言，让用户始终待在同一个页面上则更有必要。

渐进式展现：基于用户的操作/某种特定规则，渐进式展现不同的操作选项。
![](https://os.alipayobjects.com/rmsportal/xpynnwXnfCpGHvn.png)

配置程序：通过提供一系列的配置项，帮助用户完成任务或者产品组装。
![](https://os.alipayobjects.com/rmsportal/EBVLFAwHHjiXtIJ.png)

弹出框覆盖层：虽然弹出框的出现会打断用户的心流，但是有时候在弹出框中使用『步骤条』来管理复杂流程也是可行的。

![](https://os.alipayobjects.com/rmsportal/xcYosQncDPuFxhS.png)
