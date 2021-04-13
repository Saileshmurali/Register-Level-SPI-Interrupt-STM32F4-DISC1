# Register-Level-SPI-Interrupt-STM32F4-DISC1
This repository interfaces ADXL345 accelerometer with the STM32F4 discovery board using external interrupt.
Data is sampled at 100Hz. PA0 is configured as external interrupt and should be connected to INT2. PA4 is CS, PA5 is Clock, PA6 is MISO, PA7 is MOSI.
