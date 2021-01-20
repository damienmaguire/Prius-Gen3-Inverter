# Prius-Gen3-Inverter
Open source logic board to control the Toyota Prius Gen 3 Inverter

PCB Files in DesignSpark PCB 8.1 Format

Based on the Open Source Inverter system designed by Johannes Heubner.


27/11/18 Reverse engineering of the inverter continues. Now have all but two of the fifty pins of the igbt interface connector worked out.


01/12/18 Uploaded design for a simple breakout pcb to allow easier access to the 50 Way JST header used for connecting to the IGBT driver board.


01/03/19 Uploaded PDF of V1 logic board design for Gen 3 inverter / converter. Design on PCB commenced. Full design to be released soon.


06/03/19 : Initial release of V1 logic board design files and Gerbers. Changes likely before prototype ordering. BOM on the way.


12/03/19 : Released final design files. Now gone for pcb prototype build. Standby for fun:)

20/01/20 : Design files released for V2 board. Uses MG2 as inverter and MG1 and boost converter for battery charging. Based on the openinverter system. PCB files in DesignSpark PCB 9 format.

16/05/20 : Design files for new V1c board released.
<br>
Instalation video manual part one :
<br>
https://youtu.be/QE-zym8iIgM
<br>
Available on the webshop here :
<br>
https://www.evbmw.com/index.php/evbmw-webshop/toyota-built-and-tested-boards

28/06/20 : Road testing : https://youtu.be/Bs4mdTkqKXk

15/09/20 : New V1d Dual Motor version gerbers and schematics uploaded. This version features two STM32 MCUs to allow Both MG1 and MG2 in a Toyota hybrid transmission to be each controlled together or independently. Untested as of this date. Sources will be released in the future.

14/10/20 : Block 3 versions of V1c and V1d boards added. Changes :

V1c - Updated obsolete SG3204 charge pump -5v supply to LM2776.

V1d - Changed pullups / pulldowns on the MG1 MCU to avoid it being detected as a Tesla M3 board by the firmware.

V1d - Updated obsolete SG3204 charge pump -5v supply to LM2776.

Dual motor board working :

https://www.youtube.com/watch?v=aW6XFF3Rs8Q

18/01/2021 :(180Jacob) Small board layout of V1d uploaded. Note at time of writing, the low side output drivers are out of stock at JLC so I will change the BOM once an alternative is chosen.


20/01/21 : Added Sync serial data captures between new VCU and bench rig (ct200h) and various prius and yaris bare logic boards.

