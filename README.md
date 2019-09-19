# [CH572](https://github.com/SoCXin/CH572)

* [WCH](http://www.wch.cn/)：[RISC-V](https://github.com/SoCXin/RISC-V)
* [L1R1](https://github.com/SoCXin/Level): 100 MHz

## [简介](https://github.com/SoCXin/CH572/wiki)

[CH572](https://www.wch.cn/products/CH572.html)是集成2.4G无线通讯的RISC-V MCU/SoC。片上集成了2Mbps低功耗蓝牙BLE通讯模块、USB全速控制器及收发器、电压比较器CMP、按键检测模块、SPI、串口、I2C等丰富的外设资源。CH572内置了LDO5V调压器产生3.3V，支持单一3.3V或单一5V电源供电，支持单线或双线仿真调试，适用于2.4G无线通讯应用和低引脚数的简单蓝牙应用。

CH570是低功耗的2.4G无线通讯MCU/SoC，不支持蓝牙，其它模块参考CH572。

``` mermaid
gantt
    title CH572 EVT
    dateFormat  YYYY-MM-DD
    section Mainline Release
    v1.1           :a1, 2024-03-17, 2025-03-19
```

### 关键特性

* 100MHz RISC-V3C, 支持RV32IMBC指令集和自扩展指令
* 12KB SRAM + 256KB Flash
* 内置5V转3.3V调压器LDO5V
* 内置2.4GHz RF收发器和基带及链路控制，支持BLE5.0
* 支持2Mbps、1Mbps
* 支持2.4G模式下最高8kHz上报率
* 接收灵敏度-95dBm，可编程+7.5dBm发送功率
* 提供优化的协议栈和应用层API，支持组网
* 支持20路按键检测，包括10路矩阵区按键和10路独立区按键
* 内置全速USB2.0控制器及PHY，支持全/低速 Host/Device
* 内置RTC，支持定时和触发两种模式
* 内置模拟电压比较器CMP，16档参考电压，等效为4位ADC
* 提供1组UART，1组SPI，6路PWM ，1路I2C
* 12个GPIO，其中1个支持5V信号输入
* 内置AES-128加解密单元，芯片唯一ID
* 封装：QFN20、DFN10X3、TSSOP16、SOP8

## [资源收录](https://github.com/SoCXin)

* [参考资源](src/)
* [参考文档](docs/)
* [参考工程](project/)
* [mounriver](http://www.mounriver.com/download)

## [选型建议](https://github.com/SoCXin)

[CH572](https://github.com/SoCXin/CH572)

