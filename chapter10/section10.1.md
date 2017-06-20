# 10.1 提示信息

任何一个产品，即使用户界面做的再好，也离不开用户引导和信息提示。提示信息是用来告诉用户需要知道什么、采取什么样行动的内容。
### 警告

#### 警告提示（Alert）

是一种非阻碍式的信息展示，它不打断用户的当前操作，一般停留至页面某个位置（优先顶部），非浮层的静态展现形式，始终展现，不会自动消失，用户可以点击关闭。
>注：关闭按钮可根据业务需要增加或隐藏。

![enter image description here](https://zos.alipayobjects.com/rmsportal/MPBsvIMFPMeocAailbIW.png)




### 通知

#### 通知提醒（Notification）
系统主动推送的重要的全局性通知信息，在系统右上角显示。
![enter image description here](https://zos.alipayobjects.com/rmsportal/icHybUesGmjYbfxfSoQY.png)
较为复杂的通知内容时使用。


### 徽标数（Badge）


用于聚合型的消息提示，一般出现在通知图标或头像的右上角，通过醒目的视觉形式吸引用户眼球。
>注：相对重要和用户关联度更高的信息提示，使用数字精准提示；权重不高和不是用户特别关心的消息提示，使用红点做提示。

![enter image description here](https://zos.alipayobjects.com/rmsportal/tmthsGOQKqdMUEAFeTYT.png)
当有 icon 的情况时一般居于 icon 右上角；无 icon 的情况下一般位于标题后侧。

### 帮助
#### 气泡卡片（Popover）

![enter image description here](https://zos.alipayobjects.com/rmsportal/vDfayzqikMEWAcTrXRzD.png)
当目标元素有进一步的描述和相关操作时，可以收纳到卡片中，根据用户的操作行为进行展现。
>注：和 Tooltip 的区别是，Popover 可以承载更复杂的内容，比如链接或按钮等。

### 文字提示（Tooltip）
![enter image description here](https://zos.alipayobjects.com/rmsportal/oOXzRKnHokbLCbRWPNrk.png)

用于精确地描述被指向的对象，例如图标、图形、链接等，鼠标移入则显示提示，移出消失，不承载复杂文本和操作。
