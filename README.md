# Java-GUI-小游戏

### 介绍
学习过程中练手的几个java-gui小游戏 <br/>
学习教程来自B站各大IT类up主

### 游玩教程
play文件夹下是.exe可执行程序，需要电脑自带java环境


### 更新内容
 **2021/11/18**：
    * 添加了贪吃蛇小游戏（长度达到550取得胜利！)
    * 添加了桌球小游戏1.0，作者已将学习的耦合版完全解耦并修复了少许错误
 **2021/11/20**：
    * 添加了黄金矿工小游戏（关卡达到50取得胜利！)
    * 新增了贪吃蛇小游戏选择困程度的功能


### 参与贡献
MGXieYang 100%

### 额外内容
如果想起什么会额外补充<br/>
<br/>

>#### 桌游小游戏1.0
>学习于尚学堂的视频，由于解耦视频不完整，为了让它实现真正的面向对象，作者没有放弃这个半成品，完成了解耦合，并修正了原视频在解耦合的三处错误。<br/>
>>错误1：DirectionComponent类中的有参方法中，不是调用类中的frame，this.frame.addMouseListener()；而是应该直接调用形参frame.addMouseListener();<br/>
>>错误2：在鼠标监听事件中，给白球赋速度值应该是 whiteBall.setSpeed(20) ; 而不是whiteBall.speed=20;<br/>
>>错误3：在鼠标监听事件中，给白球赋角度值应该是 whiteBall.setDegree(GameUtils.getAngle((int)start_x,(int)start_y,(int)end_x,(int)end_y)); 而不是degree = GameUtils.getAngle((int)start_x,(int)start_y,(int)end_x,(int)end_y);<br/>
