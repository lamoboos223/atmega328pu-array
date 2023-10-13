

## USAGE

1- upload the sketch arduino_as_ISP to your arduino uno

2- place the folder `hardware` in the arduino path in your system and restart arduino IDE.

3- connect the arduino in the pcb and select from the boards `atmega328 on a breadboard (8 MHz internal clock)`

4- connect your atmegas to the pcb.

5- change the programmer in Tools section to `AVRISP mkll` and then click burn bootloader.

6- now go to the folder `atmega_test` and click `sketch` --> `upload using programmer`

7- refer to the image `atmega328PU pins numbers` to see the location of pin `19`.
