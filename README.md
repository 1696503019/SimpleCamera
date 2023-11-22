# SimpleCamera
一个简单的相机插件, 源自于可视化项目.
具有顺滑移动, 跳转的功能.
以接口提供规范为主, 实现载体为次.

若要开启弹簧臂碰撞检测, 请在项目设置中添加Trace Channels, 并且给SpingArm设置相同的Probe Channel;
若要开启移动碰撞检测, 请在项目设置中添加Trace Channels, 并将pawn中的Trace Channel变量修改为相同的值, 这两条可以是同一个值;
