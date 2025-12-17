# Keyestudio Sensor Shield V2 for BBC micro:bit

![image-20251217105022345](./media/image-20251217105022345.png)

## 1.Description

In the educational market, micro:bit control boards are becoming more and more
popular. However, a single micro:bit control board is not easy to test with other
sensor modules. We particularly design this ke estudio sensor expansion board
V2 for micro:bit.
The sensor shield V2 breaks out all the PIO ports on the micro:bit control board
into 3PlN interface (GND, VCC, Signal), very easy to connect the micro:bit control
board and other sensor modules.

Moreover, it also extends some commonly-used serial communication interfaces
into pin or female headers with 2.54mm pin pitch, such as 12C and SPI
communication pins. So that this shield will allow communication between
micro:bit control board and other communication devices.
You can power the micro:bit board through a black DC jack (DC 7-9V) or a mciro
USB port (DC 5V) on the shield.
When power the sensor, you could select the supply voltage 3.3V or 5V via
jumper cap VI and V2.

**Special note:**
**when connect external sensor module to the shield for working,the operating**
**current of AMSI 117-3.3V and NCPI 117ST50T3G chip is too large, so it is easy to**
**get hot. Pay special attention to avoid touching the two chips and causing burns.**

## 2.Controller Compatible

micro:bit control board(V2)

## 3.Technical Details

- Power input: black DC jack (DC 7-9V) or micro USB port (DC 5V)
- Voltage output: select 3.3V or 5V via jumper cap VI/V2
- Comes with a power indicator
- Extends the PIO of micro:bit into 3PlN interface
- Serial communication pin
- 12C communication pin
- SPI communication pin
- Dimensions: 65mm x58mm x12mm
- Weight: 31 g

![image-20251217105316350](./media/image-20251217105316350.png)

**PINOUT Diagram**

![image-20251217105353723](./media/image-20251217105353723.png)

|         Picture          | V1 Interface voltage | V2 Interface voltage |
| :----------------------: | :------------------: | :------------------: |
| ![img](./media/wps1.jpg) |         3.3          |         3.3          |
| ![img](./media/wps2.jpg) |         3.3          |          5           |
| ![img](./media/wps3.jpg) |          5           |          5           |
| ![img](./media/wps4.jpg) |          5           |         3.3          |

## 4.Example Use

Send the code to your micro:bit board, and insert it into the sensor shield. Then
set the VI and V2 to 5V output, power it via DC jack (DC7-9V). Connect the LM35
sensor and 12C 1602 LCD to the sensor shield using jumper wires. Finally display
the current temperature value on the LCD. You could refer to an example picture
below.

![image-20251217105534729](./media/image-20251217105534729.png)