# 2020SMU-RM-VISION

BY SMU AJI 视觉组 李泽森 陈炳强 山川  
特别感谢：parker  https://github.com/iParkerSr

代码基于大疆开源修改  
删除了ARM下的加速neon指令，使代码能在x86平台下运行  
修改内容https://lovelive.net.cn/2020/01/12/1/  
删除了过时的大符（rune）代码  
调用了USB端口通过usb转TTL进行数据传输  
调整了部分摄像头曝光参数  
目前能实现的功能为装甲板识别  

使用方法  
下载zip或者clone整个项目  
使用qt打开.pro文件即可编译  

运行报错可能问题  
未接摄像头，无法打开摄像头  
ubuntu无法识别摄像头端口（重新插拔摄像头可以解决）  
无法打开port（插入usb转TTL可以解决）
