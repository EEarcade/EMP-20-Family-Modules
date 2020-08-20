EMP-20 Family Modules

Family Modules for the Needham's EMP-20 are required to write to / read from EPROM chips. Different Modules are used for different sets of chips. 

This project came about from TubeTimeUS's project of a universal module that can be found here: https://github.com/schlae/EMP-20Module

As of today modules:

01A/B
02A/B
03A/B
04A/B

have already been created and the gerber files are ready for download. The below chart will be updated with information when it is available. I will also do my best to update the original project to give back where possible.



| Module ID | Name                   | ID code | Grounds    | Point-to-point                                                                |  Special                             
| :-------: | ---------------------- | :-----: | :--------: | ----------------------------------------------------------------------------- | -------- 
|       01A | Standard EPROM         | 1       | 2          | 17->72, 19->62, 25->70, 28->58, 29->68, 32->56, 33->66                        |
|       01B | 16 bit EPROMS          | 2       | 21, 21     | 3->68, 23->62, 40->58, 45->70                                                 |
|       02A | Intel 8048/49/51/52 uP | 3       | 2, 19      | 11->72, 13->70, 23->68, 28->62, 32->58, 45->54                                |
|       02B | 87X7xx                 | 4       | 66         | 2->70, 6->68, 14->72, 18->58, 25->56, 29->54                                  |
|       03A | PAL 16V8/20V8/22V10    | 5       | 2          | 6->62, 16->72, 18->68, 20->58, 21->56, 22->70, 25->54,                        | 14->150pF-\>GND
|       03B | GAL 16V8/22V10, etc    | 6       | 2          | 3->62, 5->55, 7->61, 18->72, 21->70, 22->58, 24->56, 25->68, 28->64, 29->66   |
|       04A | PIC16C5x family        | 7       | 45, 64     | 10->72, 11->62, 22->58, 26->56, 33->66                                        | 12->100 ohm->70, 29->100 ohm->68
|       04B | Serial EEPROMS         | 8       | 16, 19, 66 | 2->70, 3->68, 5->56, 7->72, 9->62, 17->18->54, 21->58                         |
|       05A | Zilog Z86              | 		   |
|       05B | Zilog Z86              |         |
|       06A | Zilog Z86              |         |
|       06B | Zilog Z86              |         |
|       07A | Xicor PAL              |         |
|       07B | n/a                    |         |
|       08A | Cypress EPROMS         |         |
|       08B | Large EPROM/flash      |         |
|       09A | 68HC705, MACH          | 17      | 2, 46       | 4->72, 19->70, 26->58, 29->62, 36->68, 38->60, 45->56                        |
|       09B | 67HC711                | 18      | 41, 64      | 3->44->56, 10->70, 11->62, 13->72, 22->68, 40->58                            |
|       10A | EEPROM                 |         |
|       10B | n/a                    |         |
|       11A | PEEL devices           | 21      | 2           | 3->68, 4->70, 14->72, 18->58, 20->62, 21->56, 24->60, 25->54                 |
|       11B | TMS7782                | 22      | 45, 64      | 2->72, 11->68, 15->58, 16->70, 18->62, 28->56, 33->54                        |
|       12A | PSD                    |         |
|       12B | n/a                    |         |
|       13A | Altera EP devices      |         |
|       13B | Altera                 |         |
|       14A | Atmel 22V10            | 27      | 2           | 4->72, 14->70, 16->58, 24->56, 25->60                                        | 3-> -\|<- 1N5818 ->68 |
|       14B | ATV2500                | 28      | 21          | 3->56, 5->58, 22->60, 36->72, 37->70                                         | 2-> -\|<- 1N5818 ->68 |
|       15A | 29F100/200             |         |
|       15B | EP1800                 |         |
|       16A | GAL26V12               | 31      | 15          | 16->68, 26->58                                                               |
|       16B | PIC16C6x/PIC17Cxx      | 32      | 22, 23      | 25->54, 40->68                                                               |
|       17A | 62Txx                  |         |
|       17B | 62T/Exx                |         |
|       18A | PEEL/ATTiny/X76        | 35      | 2           | 5->68, 6->70, 8->62, 9->56, 16->72, 24->60, 25->54                           |  
|       18B | PIC16Cxx               | 36      | 66          | 13->58, 14->68, 18->23->70, 20->25->72, 28->56, 40->54 | 
|       19A | XC72xx                 |         |
|       19B | XC95xx (Xilinx)        |         |
|       20A | XC72xx                 |         |
|       20B | n/a                    |         |
|       21A | n/a                    |         |
|       21B | AT17Cxx                |         |
|       22A | 29F002                 |         |
|       22B | 29F1xx                 |         |
|       23A | Atmel 150x family      |         |
|       23B | ATV2500                |         |
|       24A | COP87xx                |         |
|       24B | COP87xx                |         |
|       25A | AT22V10B               |         |
|       25B | P51-XA-G1              |         |
|       26A | PIC14000               |         |
|       26B | 22V10                  |         |
|       27A | 26C512                 |         |
|       27B | Z86                    |         |
|       28A | PIC12C families        | 55      | 20, 21, 64    | 2->56, 3->68, 8->70, 9->72, 46->62                                         |
|       28B | P28F002                | 56      | 6, 32         | 18->20->68, 23->62, 25->58                                                 |
|       29A | 29F070-psop44          |         |
|       29B | 27SF010                |         |


# License

This work is licensed under a Creative Commons Attribution 4.0 International
License. See [https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/).
