This is STM32F103 Altera USB Blaster clone based on Satoshi OJIKA  (http://sa89a.net) PIC18 code. 
Currently only JTAG mode supported (but is easy to add SPI)  The STM32 code is quite messy 
(eg. added dirty workaround in usb_core.c to handele USB vendor requests) 
But it work hopefully  correctly 
(tested on Quartus II v11 standalone programmer with  MAXII and MAX3000 CPLD)
