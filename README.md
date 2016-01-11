# mTips
移动web: 消息弹出框

--------------------------------------

##两种调用方式
1 Tips.alert('内容')
2 Tips.alert({
	content: '内容'
});

##三种弹出方法
1 Tips.alert()
2 Tips.confirm()
3 Tips.open()

##特色的事件选项
* before: 点击确定按钮 关闭弹出框前 执行函数  (Tips.alert Tips.confirm中有效)
 		如果函数返回false 则不会执行(关闭弹出框)和(after) 一般用于做一些检测
* after: 点击确定按钮 关闭弹出框后 执行函数 (Tips.alert Tips.confirm中有效)

##自定义按钮文本
* define: 定义确定按钮的文本 (Tips.alert Tips.confirm中有效)
* cancel: 定义取消按钮的文本 (Tips.confirm中有效)

...