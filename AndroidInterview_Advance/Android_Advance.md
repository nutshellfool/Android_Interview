# Android 面试题

* 设计一个应用，完成以下功能：  
  
  * 应用启动后显示launch Image  
  * 如果用户不点击launch Image， 3秒钟后跳转到主页面。  
  * 如果用户点击launch Image， 立即跳转到主页面  

* 如何布局支持各种屏幕大小？  

  * 如果手机和平板的布局设计不一样该怎么做？  
  * 如果手机和平板的布局设计一样该又怎么做？  

* Listview 中的OnItemClicked 事件无法相应事件，怎么解决？

* 统计一个ViewGroup中包含的子view的个数

  * 可以使用的API

    * ViewGroup#getChildCount()
    * ViewGroup#getChildAt(int )

  * 请实现递归和非递归两个版本
  