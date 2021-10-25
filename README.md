# DW1000通信工程
## 简介
实现使用DW1000模块通信
## 引脚分配
- STM32L475引脚分配

    引脚|功能
    -|-
    PB12| _DW1000_SPI片选引脚CS_
    PB13| _DW100_SPI时钟引脚SCK_
    PB14| _DW100_SPI_MISO_
    PB15| _DW100_SPI_MOSI_
    PC2|_DW1000中断引脚 IRQ_
    PD12|_DW1000复位引脚 RST_
    PD10|_按键KEY0_
    PD9|_按键KEY1_
    PD8|_按键KEY2_
    PE7|_RGB灯R_
    PE8|_RGB灯G_
    PE9|_RGB灯B_
    PA9|_串口1 TX_
    PA10|_串口1 RX_

- STM32L0的引脚分配

    引脚|功能
    -|-
    PB11|_DW1000_SPI片选引脚CS_
    PB10|_DW1000_SPI时钟引脚SCK_
    PB14|_DW1000_SPI_MISO_
    PB15|_DW1000_SPI_MOSI_
    PB2|_DW1000中断引脚 IRQ_
    PB12|_DW1000复位引脚 RST_
    PA9|_串口1 TX_
    PA10|_串口1 RX_
