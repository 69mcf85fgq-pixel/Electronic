# Fly01 无人机项目 / Fly01 Quadcopter Project


Fly01 是一个四轴无人机学习项目，包含自主设计的飞机控制板和遥控器。

- **飞控：**STM32F411RCT6、MPU6050 姿态传感器、SPA06 气压计和 Si24R1 无线模块。
- **遥控器：**STM32F103C8T6，配有 LCD 显示屏和无线控制功能。
- **软件：**FreeRTOS、姿态反馈控制、气压定高、无线通信和遥控界面。
- **资料包：**包含两端源码和固件、Fly01 原理图与 PCB、BOM、构建和操作说明。

本项目用于学习与交流。固件主要由 AI 协助实现，作者完成了硬件设计、焊接、调试和整机测试，并反馈无人机目前运行正常。欢迎参考并提出改进建议。

使用前请阅读资料包内的说明，先拆桨检查接线、电机旋向、反馈方向和停机功能。具体实现及第三方许可见资料包内文档。


Fly01 is a quadcopter learning project featuring a custom-designed flight controller and remote controller.

- **Flight controller:** STM32F411RCT6, MPU6050 IMU, SPA06 barometer and Si24R1 wireless module.
- **Remote controller:** STM32F103C8T6 with an LCD and wireless controls.
- **Software:** FreeRTOS, attitude feedback control, barometric altitude hold, wireless communication and a remote-control interface.
- **Project archive:** Source code and firmware for both controllers, Fly01 schematics and PCB designs, BOMs, build instructions and operating guidance.

This project is shared for learning and discussion. The firmware was developed largely with AI assistance; the author carried out the hardware design, assembly, debugging and system testing, and reports that the drone is currently operating normally. Feedback and suggestions are welcome.

Before use, read the documentation in the archive. Remove the propellers when checking wiring, motor rotation, feedback direction and the stop function. See the archive for implementation details and third-party licences.
