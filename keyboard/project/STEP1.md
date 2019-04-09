## [键盘STEP1实现](https://github.com/lite-life/elite) 

MCU控制主体：N x [STM32F103](https://github.com/sochub/STM32F103) 

[返回 -> 键盘工程](../) 

该目录包括相应的工程代码，STM32F103是一颗非常常用的MCU，作为原型开发可以获得更多的资源支持和性价比

### 阶段功能预期

- 大于1000Hz高频检测按键，全键无冲
- 可实现按键压力检测
- 可实现按键的时间计量
- PWM输出控制LED
- 每键RGB三色高亮LED混光
- 高精度光强度感知
- 高精度温湿度感知
- 九轴方向感知
- 红外接近感知和悬浮控制


### 阶段工程目标

- 机械轴按键监控矩阵扫描
- LED控制，包括RGB+PWM调色
- 集成光线传感器监控环境光强
- 集成环境传感器监控环境温湿
- 集成方向传感器监控设备状态
- 集成红外收发设备实现悬浮监控

采用多颗MCU控制整个设备，包括87按键高频检测（中断检测），各类传感器的控制和RGB灯光控制


开源资源检索：

- https://github.com/viktorvano/STM32F103C8T6_HID_keyboard
- https://github.com/MightyPork/stm32f103-usb-keyboard
- https://github.com/Beastmaster/stm32f103_usb_hid
- https://github.com/Pekaso/pillcase36