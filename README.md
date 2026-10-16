A DC motor driver board built around an Artery AT32F423CBT7 MCU. It drives a single brushed DC motor through an H-bridge of four
100 V N-channel MOSFETs, measures the current in each half-bridge with shunt resistors and op-amps, and talks over CAN and UART.
Quadrature encoder feedback is supported.

The driver should work fine with 4s lipo batt. If you want to use 3s, bridge the 12V regulator.
