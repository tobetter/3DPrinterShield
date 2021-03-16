## 3D Printer Shield 

"3D Printer Shield" is a board to run 3D printer using ODROID single board
computer, technically this board is designed to control the motor driver
modules with TMC2209 (UART) or TMC2130 (SPI) through the on-board GPIO
headers without an additional processessor.

![3D Printer Shiled on ODROID-N2Plus and ODROID-C4](images/pcb_assembled2.jpg)

Originally this project is started to use RAMPS 1.6, but has changed to design
a new board since board connection is quite different.

[![](http://img.youtube.com/vi/o2U3yanucio/0.jpg)](http://www.youtube.com/watch?v=o2U3yanucio "")

The board has been tested with Ender-3 and runs by Klipper.

[![](http://img.youtube.com/vi/SXoTmYS2FU0/0.jpg)](http://www.youtube.com/watch?v=SXoTmYS2FU0 "")

Then later, I've built an OS image to run Klipper on ODROID-C4 and the image
can be downloaded from [the link](https://bit.ly/3ppd9lL)

[![](http://img.youtube.com/vi/UwoKeeDlM0k/0.jpg)](http://www.youtube.com/watch?v=UwoKeeDlM0k "")
