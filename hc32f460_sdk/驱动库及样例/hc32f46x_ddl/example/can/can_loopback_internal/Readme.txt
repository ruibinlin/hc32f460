﻿================================================================================
                                样例使用说明
================================================================================
版本历史 
日期        版本    负责人         IAR     MDK   描述
2018-12-25  1.0     Lux            7.70    5.16  first version
================================================================================
功能描述
================================================================================
本样例为CAN内部回环模式通信样例。


================================================================================
测试环境
================================================================================
测试用板:
---------------------
EV-HC32F460-LQFP100-050-V1.1

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
2）启动IDE的下载和调试功能，全速运行；
3) 观察发送数据是否被正常接收（stcRxFrame.Data 是否等于 stcTxFrame.Data)。

================================================================================
注意
================================================================================
该模式下，CAN IP的TX和RX默认内部互联，发送的数据直接通过内部RX被接收。

================================================================================
