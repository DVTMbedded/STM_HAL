add_library(HAL
            STM32H7xx_HAL_Driver/Src/stm32h7xx_hal.c       
            STM32H7xx_HAL_Driver/Src/stm32h7xx_hal_cortex.c
            STM32H7xx_HAL_Driver/Src/stm32h7xx_hal_exti.c
            STM32H7xx_HAL_Driver/Src/stm32h7xx_hal_gpio.c
            STM32H7xx_HAL_Driver/Src/stm32h7xx_hal_pwr.c
            STM32H7xx_HAL_Driver/Src/stm32h7xx_hal_rcc.c
            STM32H7xx_HAL_Driver/Src/stm32h7xx_hal_dma_ex.c
            STM32H7xx_HAL_Driver/Src/stm32h7xx_hal_dma.c
            STM32H7xx_HAL_Driver/Src/stm32h7xx_hal_flash.c
            STM32H7xx_HAL_Driver/Src/stm32h7xx_hal_hsem.c
            STM32H7xx_HAL_Driver/Src/stm32h7xx_hal_i2c_ex.c
            STM32H7xx_HAL_Driver/Src/stm32h7xx_hal_i2c.c
            STM32H7xx_HAL_Driver/Src/stm32h7xx_hal_i2s_ex.c
            STM32H7xx_HAL_Driver/Src/stm32h7xx_hal_i2s.c
            STM32H7xx_HAL_Driver/Src/stm32h7xx_hal_ltdc_ex.c
            STM32H7xx_HAL_Driver/Src/stm32h7xx_hal_ltdc.c
            STM32H7xx_HAL_Driver/Src/stm32h7xx_hal_mdma.c
            STM32H7xx_HAL_Driver/Src/stm32h7xx_hal_ospi.c
            STM32H7xx_HAL_Driver/Src/stm32h7xx_hal_pwr_ex.c
            STM32H7xx_HAL_Driver/Src/stm32h7xx_hal_rcc_ex.c
            STM32H7xx_HAL_Driver/Src/stm32h7xx_hal_rtc_ex.c
            STM32H7xx_HAL_Driver/Src/stm32h7xx_hal_rtc.c
            STM32H7xx_HAL_Driver/Src/stm32h7xx_hal_sd_ex.c
            STM32H7xx_HAL_Driver/Src/stm32h7xx_hal_sdram.c
            STM32H7xx_HAL_Driver/Src/stm32h7xx_hal_spi_ex.c
            STM32H7xx_HAL_Driver/Src/stm32h7xx_hal_spi.c
            STM32H7xx_HAL_Driver/Src/stm32h7xx_hal_tim_ex.c
            STM32H7xx_HAL_Driver/Src/stm32h7xx_hal_tim.c
            STM32H7xx_HAL_Driver/Src/stm32h7xx_hal_uart_ex.c
            STM32H7xx_HAL_Driver/Src/stm32h7xx_hal_uart.c
            STM32H7xx_HAL_Driver/Src/stm32h7xx_ll_delayblock.c
            STM32H7xx_HAL_Driver/Src/stm32h7xx_ll_fmc.c
            STM32H7xx_HAL_Driver/Src/stm32h7xx_ll_sdmmc.c
            STM32H7xx_HAL_Driver/Src/stm32h7xx_hal_sd.c)

target_include_directories(HAL PUBLIC STM32H7xx_HAL_Driver/Inc)
target_include_directories(HAL PUBLIC CMSIS/Include)
target_include_directories(HAL PUBLIC CMSIS/Device/ST/STM32H7xx/Include)