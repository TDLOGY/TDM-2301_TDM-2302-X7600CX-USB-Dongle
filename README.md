# TDM-2301_TDM-2302-X7600CX-USB-Dongle
SIM7600CE-USB Dongle and A7600C-L1-USB Dongle

# This repository will include all data for both TDM-SIM7600CE and TDM-A7600C-L1 module
---
__Advertisement  __
#### Order easy online at:
- __[TDM-SIM7600CE-M1S](https://linhkienthuduc.com/module-4g-3g-2g-gps-simcom-sim7600ce-m1s-lte-cat-4-ra-chan)__ - 2G/3G/4G LTE CAT 4 GPS BREAKOUT MODULE
- __[TDM-A7600C-L1](https://linhkienthuduc.com/module-4g-3g-2g-simcom-a7600c-l1-lte-cat-1-ra-chan)__ - 2G/3G/4G LTE CAT 1 BREAKOUT MODULE.
- __[A7670C-LASS](https://linhkienthuduc.com/module-4g-simcom-a7670c-lass-da-ra-chan-thay-the-module-sim800l)__ - 2G/3G/4G LTE CAT 1 BREAKOUT MODULE.
----
This repo will provide you all data for SIM7600CE USB Dongle and A7600C-L1 USB Dongle module!

### Please Note: These Dongle already intergrated a PCB Antena ( Testing purpose only), please remove the resistor in the antena and bridge the IPEX connector to use external good antena.
---

### TDM-2301-SIM7600CE USB Dongle Module Specifications:

+ General data::
  - Supply voltage: USB Port
  - Control & Data Via USB Port
  - LTE CAT 4 100M
  - Operation temperature: -40℃ to +85℃
  - Weight: : 5.7 ± 0.2g
  - GNSS:GPS/GLONASS/BeiDou
  - Frequency:
    * LTE-FDD B1/B3/B5/B8
    * UMTS/HSDPA/HSPA+ B1/B8
    * GSM/GPRS/EDGE 900/1800MHz
 ![Picture](https://github.com/TDLOGY/TDM-2301_TDM-2302-X7600CX-USB-Dongle/blob/main/SIM7600CE-M1S-USB-DONGLE2.png)
---
### TDM-2302-A7600C-L1-USB-Dongle Specifications:

+ General data::
  - Supply voltage: USB Port
  - Control & Data Via USB Port
  - LTE CAT 4 100M
  - Operation temperature: -40℃ to +85℃
  - Weight: : 5.7 ± 0.2g
  - GNSS: No
  - Frequency:
    * LTE-FDD B1/B3/B5/B8
    * UMTS/HSDPA/HSPA+ B1/B8
    * GSM/GPRS/EDGE 900/1800MHz

 ![Picture](https://github.com/TDLOGY/TDM-2301_TDM-2302-X7600CX-USB-Dongle/blob/main/SIM7600CE-A7600C-L1-USB-DONGLE2.png)

 ![Picture bottom](https://github.com/TDLOGY/TDM-2301_TDM-2302-X7600CX-USB-Dongle/blob/main/SIM7600CE-A7600C-L1-USB-DONGLE.png)
---

## Driver for windows: [DOWNLOAD HERE](https://github.com/TDLOGY/SIMCOM_USB_DRIVER)
https://github.com/TDLOGY/SIMCOM_USB_DRIVER
---

## AT Command Test GUI:

[User Guide ( Vietnamese)](https://linhkienthuduc.com/at-command-test-cho-cac-dong-module-sim)

[DOWNLOAD HERE](https://github.com/TDLOGY/ATCommand_Test)

See more our product at  [www.tdmaker.space](https://tdlogy.com/en/makerspace/)

---

## Pin Tables
| Name| Description |
| ------ | ----------- |
| 5V | Input power for module, input range from 4.8-6V, average supply current should be above 1.2A |
| GND| GND power |
| PEN| Power Enable signal control, default is pull high (active module), pull down by external npn transistor or IO to turn off the module completely |
| RTS| RTS signal for Uart flow control|
| RXD| Uart receive data|
| TXD| Uart transmit dataa|
| CTS| CTS signal for Uart flow control|
| DTR| DTR signal for Uart flow control|
| RI| RI signal |

PWR KEY Pin, default pulled down by **0 Ohm** (**R10**), to using it, please remove R10

### Pin logic level
- These pin supported to connect direct with other MCU with higher logic level (example: 3.3V, 5V, 12V..) as below:

| Name| Description |
| ------ | ----------- |
| 3.3V or 5V logic level | TX, RX, DTR, RTS, CTS, RI|

- ### SIMCOM USB Dongle Dimension

![Pinout](https://github.com/TDLOGY/TDM-2301_TDM-2302-X7600CX-USB-Dongle/blob/main/SIM7600C-USB-Dongle-Dimension.PNG)

- ### Additional Plastic case can easily buy here: 

![LINK](https://github.com/TDLOGY/TDM-2301_TDM-2302-X7600CX-USB-Dongle/blob/main/fdb7d1f3abf676a82fe73.jpg)




