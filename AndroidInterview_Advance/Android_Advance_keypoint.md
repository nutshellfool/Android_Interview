#Android 面试题考察点

1、设计一个应用，完成以下功能：  

		>> 应用启动后显示launch Image   
	launchImage Activity 的Image 充满屏幕该怎么做？ ImageView scaleMode 属性的"fitxy"   
		>> 如果用户不点击launch Image， 3秒钟后跳转到主页面。  
		>>如果用户点击launch Image， 立即跳转到主页面   
	如果使用timer完成，什么时候设置timer？（onCreat? onResume?） 什么时候取消timer？(跳转Activity后？ 跳转之后有没有finish掉自己的Activity)
	除了timer这样的实现方式，还有其他方式吗？（通过handler?）  
	比较下这两种方式。
	
2、如何布局支持各种屏幕大小？  

	>>如果手机和平板的布局设计不一样该怎么做？  
	>>如果手机和平板的布局设计一样该又怎么做？
	此题无特殊的考察点，只是需要知道对应多屏的策略和Android匹配资源的规则。