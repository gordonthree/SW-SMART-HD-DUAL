# Heavy Duty Dual Smart Switch Node

Compact power distribution module intended to control two heavy duty high-side DC loads. The module provides eFuse protection and current monitoring for each load. Module temperature and supply voltage are also monitored. This module works with other CAN-CTL modules using the robust CAN bus interface.

<IMG src="https://github.com/gordonthree/SW-SMART-HD-DUAL/blob/main/SW-SMART-HD-DUAL.png?raw=true" width=480>


* STM32G0B1KBT 32-pin microcontroller on board
* Dual Infineon BTS50010 Profet smart switches for high side loads
* Microchip MCP2562 isolated CAN bus transceiver
* Voltage divider to monitor supply voltage
* High side switch current monitoring and diagnostics
* Three position screw terminal block for CAN bus connection
* Heavy duty terminal block connectors for power in/out
* Headers for SWD programming and USART1 debug serial port