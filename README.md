Read this in other languages: [English](README.md), [日本語](README.ja.md)

# SiTCP Sample Code for KC705 SGMII

This is the SiTCP sample source code (SGMII version) for KC 705 communication confirmation.

In this code use the module that converts the interface of AT93C46, used by SiTCP, to EEPROM (M24C08) of KC705.

This code also use a module that to operate I2C switch, PCA9548A, loaded on the KC705.

Before downloading the firmware to the KC 705, please set the jumper connection of J29, J30, J64 of KC 705 as follows.

* J29: Jumper over pins No.2-3.
* J30: Jumper over pins No.2-3.
* J64: No jumper connection.

(Please see at reference Xilinx UG 810 for more information).


## What is SiTCP

Simple TCP/IP implemented on an FPGA (Field Programmable Gate Array) for the purpose of transferring large amounts of data in physics experiments.

* For details, please refer to [SiTCP Library page](https://www.bbtech.co.jp/en/products/sitcp-library/).
* For other related projects, please refer to [here](https://github.com/BeeBeansTechnologies).

![SiTCP](sitcp.png)
