# 10.2 过程反馈

操作过程中尽可能将状态的反馈给用户，即时的响应会给用户增加信赖感。
加载状态进度反馈#

![enter image description here](https://zos.alipayobjects.com/rmsportal/iwEcSHfcdVYLkcWopOzK.png)
当用户不必等待较长时间的加载时使用。
在操作需要一段时间（一般为超过2秒）完成时系统应即时给予提醒，明确告知加载的状态或加载进度条，保持与用户的沟通。

>注：若加载时间较长，应提供取消操作。

#### 录入反馈


操作过程中可通过不同的校验规则和形式，让用户及时发现并纠正错误。
>注：反馈文字紧跟着要说明的区块（反馈内容一般是错误说明），不自动消失（当用户进行相应的交互操作后才消失）。

![enter image description here](https://zos.alipayobjects.com/rmsportal/luLujTAQqovClEOmgqzj.png)


气泡确认框（Popconfirm）


和全屏居中模态对话框相比，交互形式更轻量。
![enter image description here](https://zos.alipayobjects.com/rmsportal/adnYamnCJfmYrNLZOxdn.png)
目标元素的操作需要用户进一步的确认时，在目标元素附近弹出浮层提示，询问用户。
