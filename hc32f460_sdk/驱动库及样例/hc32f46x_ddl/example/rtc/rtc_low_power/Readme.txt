﻿================================================================================
                                样例使用说明
================================================================================
版本历史
日期        版本    负责人         IAR     MDK   描述
2018-11-27  1.0     Yangjp         7.70    5.16  first version
================================================================================
功能描述
================================================================================
本样例展示Rtc模块进入低功耗功能。

说明：
本样例设置Rtc为24小时时间格式，初始化设置时间为18年10月10日下午23点59分55秒，使
用micro USB连接电脑及目标板J1口端口，打开串口调试助手，初始设置每分钟触发RTC中断
，之后进入低功耗睡眠模式，当计时到0:00:00时触发中断唤醒系统，唤醒后设RTC每秒周期
中断，通过串口每秒输出目标板时间信息，同时LED0进行闪烁。

================================================================================
测试环境
================================================================================
测试用板:
---------------------
EV-HC32F460-LQFP100-050-V1.1

辅助工具:
---------------------
Micro USB数据线

辅助软件:
---------------------
串口调试助手

================================================================================
使用步骤
================================================================================
1）打开工程并重新编译；
2）使用USB线连接电脑及目标板，设置波特率为115200，在串口调试助手上打开USB对应串口；
3）启动IDE的下载程序功能，关闭IDE下载界面；
4）等待5秒后RTC唤醒系统，观察串口打印的时间信息，并观察LED0闪烁情况；

================================================================================
注意
================================================================================
无

================================================================================
