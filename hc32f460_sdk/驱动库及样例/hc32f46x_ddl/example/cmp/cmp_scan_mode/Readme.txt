﻿================================================================================
                                样例使用说明
================================================================================
版本历史
日期        版本    负责人         IAR     MDK   描述
2018-10-22  1.0     Pangw          7.70    5.16  first version
================================================================================
功能描述
================================================================================
本样例主要展示CMP的扫描比较功能。
说明：
样例连续扫描检测INP1和INP2，通过VCOUT引脚，查看检测状态。

================================================================================
测试环境
================================================================================
测试用板:
---------------------
EV-HC32F480-LQFP144-050-V10

辅助工具:
---------------------
示波器Tektronix DPO 2024B

辅助软件:
---------------------
无

================================================================================
使用步骤
================================================================================
1）J25通过跳冒连接，断开J24跳冒并将J24-VRO与J6-29连接，J9-84与J6-30连接，J8-52与示波器连接
2）打开工程编译并全速运行
3）调节可调电阻R138调制为最小阻值
4）观察示波器，显示连续脉冲方波，表示INP1电压输入高于INM电压
5）按下SW2不释放，示波器显示低电平，表示INP1电压输入低于INM电压
6）按下SW2不释放，调节可调电阻R138调制为最大阻值
7）示波器显示连续脉冲方波，表示INP2电压输入高于INM电压
8）按下SW2不释放，调节可调电阻R138调制为最小阻值
9）示波器显示低电平，表示INP2电压输入低于INM电压
10）重复步骤3）~步骤9）

================================================================================
注意
================================================================================
更改CMP单元时，需重新配置对应的引脚、INP、INM等

================================================================================
