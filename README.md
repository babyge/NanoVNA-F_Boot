# NanoVNA-F_Boot
NanoVNA-F BootLoader,STM32F1+SPI FLASH+USB Device Mass Storage for IAP

USE  STM32CubeMX 4.27.0 V1.0
1、HAL Lib：STM32Cube_FW_F1_V1.6.1
2、MDK Ver：uVision V5.23.0.0
3、MDK Pack : ARM::CMSIS Ver: 5.2.0(2017-11-16)
4、MDK Pack : Keil::STM32F1xx_DFP Ver: 2.3.0(2018-11-05)
CHIP: STM32F103VET6 FLASH: 512 KB, SRAM: 64 KB
* HAL Lib Path: 
C:/Users/S04/STM32Cube/Repository/STM32Cube_FW_F1_V1.6.1/Drivers/STM32F1xx_HAL_Driver/Inc
C:/Users/S04/STM32Cube/Repository/STM32Cube_FW_F1_V1.6.1/Drivers/STM32F1xx_HAL_Driver/Inc/Legacy
C:/Users/S04/STM32Cube/Repository/STM32Cube_FW_F1_V1.6.1/Drivers/CMSIS/Device/ST/STM32F1xx/Include
C:/Users/S04/STM32Cube/Repository/STM32Cube_FW_F1_V1.6.1/Drivers/CMSIS/Include
C:/Users/S04/STM32Cube/Repository/STM32Cube_FW_F1_V1.6.1/Middlewares/Third_Party/FatFs/src
C:/Users/S04/STM32Cube/Repository/STM32Cube_FW_F1_V1.6.1/Drivers/CMSIS/Lib/ARM/arm_cortexM3l_math.lib
* FatFs Ver：
R0.11 (February 09, 2015)
C:/Users/S04/STM32Cube/Repository/STM32Cube_FW_F1_V1.6.1/Middlewares/Third_Party/FatFs

SPI Flash: W25Q128JVSIQTR

on PC side, act as a Udisk.
![PC Udisk](/Img/PC.jpg)

on STM32 side, FatFs can read.
![FatFs](/Img/STM32.jpg)