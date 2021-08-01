# **PMW3360**
PMW3360 breakout board for trackball/mouse. Compatible with 1.8V - 5.5V Vcc.
![](/img/sensor1.jpg)

## [Project page on EasyEDA](https://easyeda.com/pigboard/pmw3360-sensor-board)

## **BOM**
|Name                       |Value  |Footprint  |Qty    |
|:---:                      |:---:  |:---:      |:---:  |
|C1,C3,C6,C7,C9,C12,C13     |100nF  |0805       |7      |
|C2,C5                      |1uF    |0805       |2      |
|C4,C8,C11,C14              |10uF   |0805       |4      |
|C10                        |4.7uF  |0805       |1      |
|DMOSI,DNCS,DSCLK           |3.3V   |SOD-323    |3      |
|R1                         |52.3k  |0805       |1      |
|R3                         |37.4k  |0805       |1      |
|R4                         |39 Ohm |0805       |1      |
|R5                         |63.4k  |0805       |1      |
|R6,R7                      |10k    |0805       |2      |
|R8                         |30.1k  |0805       |1      |
|U1,U3                      |       |SOT23      |2      |
|PMW3360 + lens             |       |           |1      |

Optional (for easier prototyping)
|Name               |Qty   | Notes |
|:---:              |:---: |:---   |
|H1                 |1     |8 pin (2x4) 2.54 pitch male through hole pin header|

Remarks:
*   PCB/Holes are the same size/placement as for [ADNS-9800](https://github.com/kbjunky/ADNS9800) thus making it easier to swap sensors for existing projects
*   Diodes are 3.3V Zener diodes
*   U1, U3 are TPS73601DBVR LDO volatge stabilizers
*   8 pin male header is usefull for prototyping when sensor has to be switched between many MCUs
*   Sensor together with the lens can be obtained from [Aliexpress](https://www.aliexpress.com/item/33056166849.html?spm=a2g0o.productlist.0.0.38b76a63WwCLxK&algo_pvid=fbcd6a66-b324-4e10-9381-b374719f1ea1&algo_exp_id=fbcd6a66-b324-4e10-9381-b374719f1ea1-1)

## For ordering tips check description for [ADNS-9800](https://github.com/kbjunky/ADNS9800)





