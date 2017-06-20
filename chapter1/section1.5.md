# 1.5 简单明了

> 正如 Alan Cooper 所言：『需要在哪里输出，就要允许在哪里输入』。这就是直接操作的原理。eg：不要为了编辑内容而打开另一个页面，应该直接在上下文中实现编辑。

### 页内编辑
单字段行内编辑
当『易读性』远比『易编辑性』重要时，可以使用『单击编辑』。

![](https://os.alipayobjects.com/rmsportal/PmVuUUKeamHdveT.png)单击编辑示例

- 状态一：普通的浏览模式，不区分可编辑行和不可编辑行；
- 状态二：鼠标悬停时，『指针』变为『手型』，编辑区域底色变黄，出现『Tooltips』提示单击编辑；
- 状态三：鼠标点击后，出现『输入框』、『确定』、『取消』表单元素，同时光标定位在『输入框』中。



**当『易读性』为主，同时又要突出操作行的『易编辑性』时，可使用『文字链/图标编辑』。**

![](https://os.alipayobjects.com/rmsportal/ZmRlahliUbCurhu.png)文字链/图标编辑示例

- 状态一：在可编辑行附近出现文字链/图标；
- 状态二：鼠标点击『编辑』后，出现『输入框』、『确定』、『取消』表单元素，同时光标定位在『输入框』中。


----------

**多字段行内编辑**
> 注：在『多字段行内编辑』的情况下，显示的内容和编辑时所需的字段会存在比较大的差异，所以更需要『巧用过渡』原则中的『解释刚刚发生了什么』来消除这种视觉影响。

![](https://os.alipayobjects.com/rmsportal/hGXGErepBnrwqzj.png)

多字段行内编辑示例
编辑模式在不破坏整体性的前提下，可扩大空间，以便放下『输入框』等表单元素；其中，在 Table 中进行编辑模式切换时，需要保证每列的不跳动。


----------

### 利用拖放

拖放列表

只能限制在一个维度（上/下或者左/右）进行拖放。

![](https://os.alipayobjects.com/rmsportal/DjMFcqSxZrulbGF.png)

拖放列表示例

- 状态一：鼠标悬停该行时，出现可移动的『图标』；
- 状态二：鼠标悬停在该『图标』时，指针变为『手型』，点击即可进行拖动；
- 状态三：拖动到可放置区块，出现蓝色描边，告知用户该区块可放置该对象。

![](https://os.alipayobjects.com/rmsportal/KVhqdSoLUjXPXuN.png)