# TSOC_NEOLED

**TSOC_NEOLED** is a Eight-Channel WS2812 driver exapnsion board **thingSoC Reference Design.** 

**thingSoC Reference Designs** are example thingSoC implementations that implement
various reference and testing circuits for demonstrating the use of the thingSoC libraries.
These reference designs can serve as starting templates for user designs.

**TSOC_NEOLED** uses a programmable system on chip (PSoC4) with an eight (8) channel driver
to drive up to 512 WS2812 Color LED's, arranged as 64x8 (eight strings).
The **TSOC_NEOLED** can provide several different intefaces in order to make
interfacing large numbers of LED easy. Interface protocols include :

1) UART Serial DMX-512 (200K Baud, N, 8, 1) with a 512 byte frame size.
2) I2C Serial DMX-512, Memory Mapped (**TSOC_NEOLED** looks like a 512 byte I2C SRAM)
3) SPI Serial DMX-512, Memory Mapped (**TSOC_NEOLED** looks like a 512 byte SPI SRAM)


[![thingSoC TSOC_NEOLED](https://github.com/thingSoC/TSOC_NEOLED/blob/master/TSOC_NEOLED/images/TSOC_NEOLED_top.png?raw=true) 
*TSOC_NEOLED*](https://github.com/thingSoC/TSOC_NEOLED)

---------------------------------------

## TSOC_NEOLED Status <a name="TSOC_NEOLED_status"/>

**04/28/2016:** 
Revision 1.0 - New Layout with Eight(8) channel driver


---------------------------------------

## TSOC_NEOLED Documentation Index <a name="TSOC_NEOLED_documentation_index"/>

[TSOC_NEOLED Project](http://thingsoc.github.io/projects/TSOC_NEOLED.html)

[TSOC_NEOLED Hardware](https://github.com/thingSoC/TSOC_NEOLED/tree/master/TSOC_NEOLED/hardware)


---------------------------------------

## thingSoC Documentation Index <a name="thingSoC_documentation_index"/>

[thingSoC Organization Website](http://thingSoC.github.io)

[thingSoC FAQ - Frequently Asked Questions](http://thingsoc.github.io/support/faq.html)

---------------------------------------

[![thingSoC](http://thingsoc.github.io/img/projects/thingSoC/thingSoC_thumb.png?raw=true) 
*thingSoC*](http://thingsoc.github.io)