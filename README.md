# Simplified MLX90640 Driver
This project contains a simplified MicroPython driver for the MLX90640 thermal 
infrared camera. It isn't fast and it isn't pretty, but it has been shown to
work on ESP32 and STM32 processors. 

The main camera driver is by **mwerezak** and can be found at 
<https://github.com/mwerezak/micropython-mlx90640>.

Documentation is mostly found as extensive Doxygen style comments in 
`mlx_cam.py` and the pages generated therefrom (coming soon). 

This driver has been tested on a generic ESP32 development board and 
an STM32L476RG Nucleo&trade; for academic use.  There is **no guarantee**
that this driver will work for any particular purpose.  This software is
provided in the hope that it will be useful, but with **no warranty** 
whatsoever, not even the implied warranty of merchantability or fitness
for any particular purpose. 

