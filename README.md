Read this in other languages: [English](README.md), [日本語](README.ja.md)

# SiTCP Netlist for Virtex5

SiTCP Library (ngc file) for Xilinx Virtex 5.


## What is SiTCP

Simple TCP/IP implemented on an FPGA (Field Programmable Gate Array) for the purpose of transferring large amounts of data in physics experiments.

* For details, please refer to [SiTCP Library page](https://www.bbtech.co.jp/en/products/sitcp-library/).
* For other related projects, please refer to [here](https://github.com/BeeBeansTechnologies).

![SiTCP](sitcp.png)


## History

2012-11-22 Ver.6.0
* Client mode of SiTCP added.

2014-03-28 Ver.8.0
* Expansion of the ACK reply method at the time of the reception. Added minimum IPG resistor (programmable range from 3 to 15).

2017-04-21 Ver.10.0
* Added MAC address output port. RX bug fixed.

2017-05-29 Ver.11.0
* Modified for corresponding to the pause frame(IEEE802.3x flow control).
* Arp request function added in Client mode.
* SiTCP_RST modified.
* Change of ACK transmission method.
* MIF Initialization modified.
