﻿================================================================================
                                样例使用说明
================================================================================
版本历史
日期         版本    负责人        IAR     MDK   描述
2018-11-30   1.0     Husj          7.70    5.16  first version
================================================================================
功能描述
================================================================================
本样例主要展示MCU的TIMER6的硬件启动、停止、清零功能
说明：
配置timer6，hclk设置为168M
PE06（LED0)-->PWMA 
PD007(LED1)-->PWMB

硬件启动: PE06（LED0)-->PWMA 上升沿

硬件停止: PE06（LED0)-->PWMA 下降沿

硬件清零: PD007(LED1)-->PWMB 上升沿

================================================================================
测试环境
================================================================================
测试用板:
---------------------
EV-HC32F460-LQFP100-050-V1.1

辅助工具:
---------------------
示波器

辅助软件:
---------------------
无

================================================================================
使用步骤
================================================================================
1） PE06连接PE09，PD07连接PE08
2） 打开工程编译并全速运行。
3） 使用示波器观察PE06、PD07、PB05端口，
PE06上升沿时候，PB05有翻转电平输出
PE06下降沿的时候，PB05停止翻转，此时Timer61的CNTER停止计数
PD07上升沿的时候，Timer61的CNTER被清零
================================================================================
注意
================================================================================


================================================================================
