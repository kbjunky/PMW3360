# **PMW3360/PMW3389**
PMW3360/PMW3389 breakout board for trackball/mouse. Compatible with 3.3V - 5V MCUs.

![](/img/Sensor.jpg)
![](/img/Schematic.png)
![](/img/PCB.png)


## **BOM**
|Name                       |Value  |Footprint  |Qty    |
|:---:                      |:---:  |:---:      |:---:  |
|C1,C3,C6,C7,C9,C12,C13     |100nF  |0805       |7      |
|C2,C5                      |1uF    |0805       |2      |
|C4,C8,C11,C14              |10uF   |0805       |4      |
|C10                        |4.7uF  |0805       |1      |
|U2                         |       |TSSOP-14   |1      |
|R1                         |52.3k  |0805       |1      |
|R3                         |37.4k  |0805       |1      |
|R4                         |39/13* |0805       |1      |
|R5                         |63.4k  |0805       |1      |
|R6,R7                      |10k    |0805       |2      |
|R8                         |30.1k  |0805       |1      |
|U1,U3                      |       |SOT23      |2      |
|PMW3360/PMW3389 + lens     |       |           |1      |
||

Remarks:
*   PCB/Holes are the same size/placement as for [ADNS-9800](https://github.com/kbjunky/ADNS9800) thus making it easier to swap sensors for existing projects. Also in between mounting holes fits ProMicro or Rapsperry Pico thus making it possible to fit MCU underneath the sensor for a compact build.
*   U1, U3 are TPS73601DBVR LDO voltage stabilizers
*   U2 is LSF0204PWR logic level translator
*   For PMW3389 R4 must be 13 Ohm
*   Sensor together with the lens can be obtained from [Aliexpress](https://www.aliexpress.com/item/33056166849.html?spm=a2g0o.productlist.0.0.38b76a63WwCLxK&algo_pvid=fbcd6a66-b324-4e10-9381-b374719f1ea1&algo_exp_id=fbcd6a66-b324-4e10-9381-b374719f1ea1-1)
