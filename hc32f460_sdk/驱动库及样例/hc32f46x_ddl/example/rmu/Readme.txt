﻿================================================================================
                                样例使用说明
================================================================================
版本历史
日期        版本    负责人         IAR     MDK   描述
2018-10-20  1.0     Wuze          7.70    5.26  First version
================================================================================
功能描述
================================================================================
1）读取复位信息，并通过串口发送出去；
2）制造一些可通过软件实现的复位，如在使能 MPU 的时候，通过 DMA 访问被保护区域。

================================================================================
测试环境
================================================================================
测试用板:
---------------------
EV-HC32F460-LQFP100-050-V1.0

辅助工具:
---------------------
无

辅助软件:
---------------------
无

================================================================================
使用步骤
================================================================================
1）打开工程并重新编译；
2）下载程序到目标板，用串口调试助手查看复位信息；或通过修改 LED 指示位置，查看复位
   信息。

================================================================================
注意
================================================================================


================================================================================
