## [keyboard](https://github.com/lite-life/elite) 

采用分体式电路设计和控制，不同PCB主体间通过FPC连接，中断管理按键事件，各种按键信息的收集和模式学习

工程将包括相关的嵌入式驱动工程和硬件电路工程文件，相关的设计文档和用到的参考资料

- [搭配鼠标](../mouse) 
- [扩展HUB](../hub) 



### 功能迭代

- [step 1](project/STEP1.md) ：
	* 每个按键下对应单独的灯光管理，RGB+PWM实现调色
	* 内部的多传感器感知，包括闭环控制逻辑
	* 灯板的信息呈现效果
	
- [step 2](project/STEP2.md) ：
	* 模块化内部集成USB HUB
	* 针对type c接口的正反重新设计模式
	* 与主体设备间的通信和控制逻辑
	
- [step 3](project/STEP3.md) ：
	* 红外定位和红外控制
	* NFC功能实现
	* 多蓝牙和无线通信实现

- [step 4](project/STEP4.md) ：
	* 和鼠标的功能搭配实现和互补增强
	* 计算设备集成
	* 语音功能集成
	
开源项目资源检索：

https://github.com/qmk/qmk_firmware

https://github.com/tmk/tmk_keyboard

https://github.com/julbouln/stm32_mech_keyboard

https://github.com/lukas2511/STM32-USB-Keyboard