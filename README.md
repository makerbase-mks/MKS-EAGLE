# MKS-EAGLE
  Where to buy it: https://www.aliexpress.com/item/1005003352842756.html
  
  ## Brief introduction
  ![MKS Eagle](https://github.com/makerbase-mks/MKS-Eagle/blob/main/hardware/Image/MKS_Eagle.png)
  
  MKS Eagle is an integrated design version of Nano V3.0. The MCU is STM32F407VET6, which is as powerful as Nano V3. It retains the functions of Nano V3. The driver is designed as TMC2209 UART mode, and uses integrated heat dissipation and four-layer PCB optimization design
  
  MKS Eagle主板是在Nano V3基础上进行集成化设计，MCU使用STM32F407VET6，功能和Nano V3一样强悍。集成5个 TMC2209 Uart模式，并且使用一体式散热片和4层PCB设计，主板散热抗干扰更强……
  
  ## Compare between MKS Eagle and Nano V3
  | ITEMS      |  MKS Eagle  | MKS Robin Nano V3 |
  |------------|--------------------|-------------------------|
  | MCU | STM32F407VET6(168MHz) | STM32F407VGT6(168MHz) |
  | FLASH/RAM | 512KB FLASH/192KB RAM | 1024KB FLASH/192KB RAM |
  | Driver mode | Integrated TMC2209 UART | STEP/DIR;TMC UART;TMC SPI |
  | Drive signal external | No support | Support |
  | DFU mode | Support(BOOT0) | No support |
  | Reserved IO | PD14,PD1,PD0 | No reserved |
  | Firmware name | mks_eagle.bin | Robin_nano_v3.bin |
  | USB Disk | Support | Support |
  | TF card | Support(SPI3) | Support(SPI3) |
  | WIFI connect | USART1+SPI2 | USART1+SPI2 |
  | Virtural USB Device | Support | Support |
  | Motor interface | 5 axis 6 interface(Two Z axis share the same driver) | 5 axis 6 interface(Two Z axis share the same driver) |
  | PWM FAN(s) | 2 channels | 2 channels |
  | PWM TTL | Support | Support |
  | Independent serial port | Support(USART3) | Support(USART3) |
  | Power TVS protect | Support | Support |
  | EEPROM | 4KB AT24C32DM on board | 4KB AT24C32DM on board |
  | SPI Flash | 8M on board | 8M on board |
  | LCD support | MKS TS35/MKS MINI12864 V3/MKS H43/LCD12864/LCD2004 | MKS TS35/MKS MINI12864 V3/MKS H43/LCD12864/LCD2004 |
  
  - Special function 
    - Support power spike processing, protection circuit
	- Support power reverse connection protection
	
  ## Hardware
  - Refer to hardware path file
  
  ## Firmware
  - Support Marlin 2.0
  - Support Klipper

  
  
  
