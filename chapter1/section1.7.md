# 1.7 简化交互

根据费茨法则（Fitts's Law）所描述的，如果用户鼠标移动距离越少、对象相对目标越大，那么用户越容易操作。通过运用上下文工具（即：放在内容中的操作工具），使内容和操作融合，从而简化交互。

> 费茨法则 ：到达目标的时间是到达目标的距离与目标大小的函数，具体：。其中：1.设备当前位置和目标位置的距离（D）；2.目标的大小（W）。距离越长，所用时间越长；目标越大，所用时间越短。

1. 实时可见工具
2. 悬停即现工具
- 开关显示工具
- 交互中的工具
- 可视区域 ≠ 可点击区域

### 实时可见工具

如果某个操作非常重要，就应该把它放在界面中，并实时可见。

![](https://os.alipayobjects.com/rmsportal/sfytaOSssRrdYFg.png)

实时可见工具示例 --

- 状态一：在文案中出现一个相对明显的点击区域；
- 状态二：鼠标悬停时，鼠标『指针』变为『手型』，底色发生变化，邀请用户点击。
- 状态三：鼠标点击后，和未点击前有明显的区分。


### 悬停即现工具

如果某个操作不那么重要，或者使用『实时可见工具』过于啰嗦会影响用户阅读时，可以在悬停在该对象上时展示操作项。

![](https://os.alipayobjects.com/rmsportal/AUiWMlbxCvpBFyA.png)悬停即现工具示例

鼠标悬停时，出现操作项。


### 开关显示工具

如果某些操作只需要在特定模式时显示，可以通过开关来实现。

![](https://os.alipayobjects.com/rmsportal/uGWcpAFgWdynxBy.png)

开关显示工具示例

用户点击『修改』后，Table 中『文本』变成『输入框』，开启编辑功能。


### 交互中的工具

如果操作不重要或者可以通过其他途径完成时，可以将工具放置在用户的操作流程中，减少界面元素，降低认知负担，给用户小惊喜。

此处也可以运用『提供邀请』 相关的知识点。

![](https://os.alipayobjects.com/rmsportal/STvIHSgnVAHOVHl.png)

推荐示例

鼠标悬停时，出现 Tooltips 进行提示，用户点击内容直接复制。

![](https://os.alipayobjects.com/rmsportal/aRihOoBCQHGATBA.png)
推荐示例![](http://img.hb.aicdn.com/b49d5ad38bcfc1a03cba2b5f576ba413db11d2641d34-E9Mdqo_fw658)

鼠标滑选/双击时，系统自动复制该部分内容。通过大胆猜测用户的行为，并帮助完成，给用户小惊喜。


### 可视区域 ≠ 可点击区域

在使用 Table 时，文字链的点击范围受到文字长短影响，可以设置整个单元格为热区，以便用户触发

![](https://os.alipayobjects.com/rmsportal/bCrBxGPJiDvkyOH.png)

![](https://os.alipayobjects.com/rmsportal/dSehXwUuXDFDhJO.png)
按钮热区示例

鼠标移入按钮附近，即可激活 Hover 状态。
