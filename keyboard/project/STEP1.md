## [键盘实现](https://github.com/lite-life/elite) 

MCU主体：[STM32F103C8T6](https://github.com/sochub/STM32F103C8) 

包括相应的工程代码，STM32F103C8T6是一颗最常用的MCU，作为原型开发可以获得更多的资源支持和性价比（量产不建议）

[返回键盘工程](../) 


- 每个按键下对应单独的灯光管理，RGB+PWM实现调色
- 内部的多传感器感知，包括闭环控制逻辑
- 灯板的信息呈现效果


采用多颗STM32F103C8T6 MCU控制整个键盘设备，包括87按键高频检测，各类传感器的控制和RGB灯光控制