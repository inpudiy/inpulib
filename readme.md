# Inpulib

![Image](images/preview.png)

This repository is a **DIY Mechanical Keyboard KiCad Library** created for hobbyists, custom keyboard builders, and electronics designers.
It provides a complete set of **schematic symbols** and **footprint libraries** for designing mechanical keyboard PCBs in KiCad.

The library covers the most commonly used components in keyboard design:

* **Switches** – MX, Kailh Choc, Alps, and other profiles
* **Momentary buttons, rotary encoders, and toggle switches** – for reset inputs, and on/off control
* **Controllers** – Pro Micro and other compatible boards
* **Connectors** – for displays, battery connections, TRRS/Audio jacks
* **Diodes** – standard components for matrix wiring

With these libraries, you can quickly integrate standard parts into your schematic and PCB layout, saving time and ensuring compatibility with popular keyboard components. 

## Footprint

### swtiches pretty

Name   | Description/notes| Preview  |
-------|-----------------------------|-------
SW_Alps_TH | Alps/Matias switch, through hole | ![SW_Alps_TH](images/footprint/swtiches/SW_Alps_TH.png)
SW_B3G-S_TH | B3G-S switch, through hole | ![SW_B3G-S_TH](images/footprint/swtiches/SW_B3G-S_TH.png)
SW_CPG1316 | CPG1316 switch, SMD, one side | ![SW_CPG1316](images/footprint/swtiches/SW_CPG1316.png)
SW_CPG1316_Reversible | CPG1316 switch, SMD, reversible | ![SW_CPG1316_Reversible](images/footprint/swtiches/SW_CPG1316_Reversible.png)
SW_Choc_Mini_TH | Choc Mini switch, through hole, one side | ![SW_Choc_Mini_TH](images/footprint/swtiches/SW_Choc_Mini_TH.png)
SW_Choc_V1V2_HS | Choc V1/V2 switch, hot-swap, one side | ![SW_Choc_V1V2_HS](images/footprint/swtiches/SW_Choc_V1V2_HS.png)
SW_Choc_V1V2_HS_Reversible | Choc V1/V2 switch, hot-swap, reversible | ![SW_Choc_V1V2_HS_Reversible](images/footprint/swtiches/SW_Choc_V1V2_HS_Reversible.png)
SW_Choc_V1V2_TH | Choc V1/V2 switch, through hole, one side | ![SW_Choc_V1V2_TH](images/footprint/swtiches/SW_Choc_V1V2_TH.png)
SW_Choc_V1V2_TH_Reversible | Choc V1/V2 switch, through hole, reversible | ![SW_Choc_V1V2_TH_Reversible](images/footprint/swtiches/SW_Choc_V1V2_TH_Reversible.png)
SW_Hi-Tek_725_TH | Hi-Tek 725 switch, through hole | ![SW_Hi-Tek_725_TH](images/footprint/swtiches/SW_Hi-Tek_725_TH.png)
SW_KS-27KS-33_HS | KS-27/33 switch, hot-swap | ![SW_KS-27KS-33_HS](images/footprint/swtiches/SW_KS-27KS-33_HS.png)
SW_KS-27KS-33_HS_Reversible | KS-27/33 switch, hot-swap, reversible | ![SW_KS-27KS-33_HS_Reversible](images/footprint/swtiches/SW_KS-27KS-33_HS_Reversible.png)
SW_KS-27KS-33_TH | KS-27/33 switch, through hole | ![SW_KS-27KS-33_TH](images/footprint/swtiches/SW_KS-27KS-33_TH.png)
SW_KS-27KS-33_TH_Reversible | KS-27/33 switch, through hole, reversible | ![SW_KS-27KS-33_TH_Reversible](images/footprint/swtiches/SW_KS-27KS-33_TH_Reversible.png)
SW_MX_HS | MX switch, hot-swap, one side | ![SW_MX_HS](images/footprint/swtiches/SW_MX_HS.png)
SW_MX_HS_Reversible | MX switch, hot-swap, reversible | ![SW_MX_HS_Reversible](images/footprint/swtiches/SW_MX_HS_Reversible.png)
SW_MX_TH | MX switch, through hole, one side | ![SW_MX_TH](images/footprint/swtiches/SW_MX_TH.png)
SW_MX_TH_Reversible | MX switch, through hole, reversible | ![SW_MX_TH_Reversible](images/footprint/swtiches/SW_MX_TH_Reversible.png)

### MCU
Name   | Description/notes| Preview  |
-------|-----------------------------|-------
U_ProMicro_RP2040_TH | Pro Micro RP2040 board, through hole | ![U_ProMicro_RP2040_TH](images/footprint/mcu/U_ProMicro_RP2040_TH.png)
U_ProMicro_nRF52840_MidMount | Pro Micro nRF52840 board, mid-mount SMD | ![U_ProMicro_nRF52840_MidMount](images/footprint/mcu/U_ProMicro_nRF52840_MidMount.png)
U_ProMicro_nRF52840_SMD | Pro Micro nRF52840 board, SMD | ![U_ProMicro_nRF52840_SMD](images/footprint/mcu/U_ProMicro_nRF52840_SMD.png)
U_ProMicro_nRF52840_TH | Pro Micro nRF52840 board, through hole | ![U_ProMicro_nRF52840_TH](images/footprint/mcu/U_ProMicro_nRF52840_TH.png)
U_ProMicro_nRF52840_TH_Reversible | Pro Micro nRF52840 board, through hole, reversible | ![U_ProMicro_nRF52840_TH_Reversible](images/footprint/mcu/U_ProMicro_nRF52840_TH_Reversible.png)
U_XIAO_nRF52840 | Seeed Studio XIAO nRF52840 board, SMD | ![U_XIAO_nRF52840](images/footprint/mcu/U_XIAO_nRF52840.png)
U_XIAO_nRF52840_Reversible | Seeed Studio XIAO nRF52840 board, SMD, reversible | ![U_XIAO_nRF52840_Reversible](images/footprint/mcu/U_XIAO_nRF52840_Reversible.png)
U_Zero_RP2040 | RP2040-Zero board, SMD | ![U_Zero_RP2040](images/footprint/mcu/U_Zero_RP2040.png)

### buttons pretty

Name   | Description/notes| Preview  |
-------|-----------------------------|-------
SW_SMD_EVQP7C01K | SPST tactile switch, SMD, 4 pins, 3.5×2.9×1.35 mm | ![SW_SMD_EVQP7C01K](images/footprint/buttons/SW_SMD_EVQP7C01K.png)
SW_SMD_L4_W3_H1.5 | SPST tactile switch, SMD, 2 pins, 4×3×1.5 mm | ![SW_SMD_L4_W3_H1.5](images/footprint/buttons/SW_SMD_L4_W3_H1.png)
SW_SMD_MSK12C02 | SPDT slide switch, SMD, 7 pins, 6.6×2.7×1.4 mm | ![SW_SMD_MSK12C02](images/footprint/buttons/SW_SMD_MSK12C02.png)
SW_SMD_TS-1289VE-4 | SPST tactile switch, SMD, 4 pins, 3.5×4.7×1.6 mm | ![SW_SMD_TS-1289VE-4](images/footprint/buttons/SW_SMD_TS-1289VE-4.png)
SW_TH_1TS002A | SPDT slide switch, through hole, 2 pins, 6×3.5×4.3 mm | ![SW_TH_1TS002A](images/footprint/buttons/SW_TH_1TS002A.png)
SW_TH_BSI-10H | SPDT slide switch, through hole, horizontal, 3 pins, 10×2.5×5.9 mm | ![SW_TH_BSI-10H](images/footprint/buttons/SW_TH_BSI-10H.png)
SW_TH_EC11E | Rotary encoder EC11E, through hole, with push button | ![SW_TH_EC11E](images/footprint/buttons/SW_TH_EC11E.png)
SW_TH_SKHLLBA010 | SPDT slide switch, through hole, horizontal, 3 pins, 7.3×3.6×4.3 mm | ![SW_TH_SKHLLBA010](images/footprint/buttons/SW_TH_SKHLLBA010.png)

### diode pretty

Name   | Description/notes| Preview  |
-------|-----------------------------|-------
D_BAV70 | Dual switching diode BAV70, SOT-23 package, SMD | ![D_BAV70](images/footprint/diode/D_BAV70.png)
D_DO-35 | General-purpose diode, DO-35 package, through hole | ![D_DO-35](images/footprint/diode/D_DO-35.png)
D_SOD-123 | General-purpose diode, SOD-123 package, SMD | ![D_SOD-123](images/footprint/diode/D_SOD-123.png)
D_SOD-323 | General-purpose diode, SOD-323 package, SMD | ![D_SOD-323](images/footprint/diode/D_SOD-323.png)
IC_SMF05CT1G | TVS diode array SMF05CT1G, SOT-23-6 package, SMD | ![IC_SMF05CT1G](images/footprint/diode/IC_SMF05CT1G.png)


## connectors pretty

Name   | Description/notes| Preview  |
-------|-----------------------------|-------
J_01x04_TH | Generic connector, single row, 1×4 contacts | ![J_01x04_TH](images/footprint)
J_01x05_TH | Generic connector, single row, 1×5 contacts | ![J_01x05_TH ](images/footprint)
J_MJ-4PP-9_TH | 4-pin jack, through-hole, TRRS compatible | ![J_MJ-4PP-9_TH](images/footprint)
J_MJ-4PP-9_TH_Reversible | 4-pin jack, through-hole, Reversible, TRRS compatible | ![J_MJ-4PP-9_TH_Reversible](images/footprint)

## symbols pretty

Name   | Description/notes| Preview  |
-------|-----------------------------|-------
Conn_01x04 | Generic connector, single row, 1×4 contacts | ![Conn_01x04](images/symbols/Conn_01x04.png)
Conn_01x05 | Generic connector, single row, 1×5 contacts | ![Conn_01x05](images/symbols/Conn_01x05.png)
D_1N4448 | High-speed switching diode 1N4448, DO-35 package, through hole, 100 V, 0.15 A | ![D_1N4448](images/symbols/D_1N4448.png)
D_1N4448W | High-speed switching diode 1N4448W, SOD-123 package, SMD, 100 V, 0.15 A | ![D_1N4448W](images/symbols/D_1N4448W.png)
D_1N4448WS | Fast switching diode 1N4448WS, SOD-323 package, SMD, 75 V, 0.15 A | ![D_1N4448WS](images/symbols/D_1N4448WS.png)
D_BAV70 | Dual switching diode BAV70, SOT-23 package, SMD, 80 V, 100 nA, Tr=10 ns | ![D_BAV70](images/symbols/D_BAV70.png)
GND | Global ground reference symbol | ![GND](images/symbols/GND.png)
PWR_FLAG | Power source flag for ERC (schematic annotation) | ![PWR_FLAG](images/symbols/PWR_FLAG.png)
IC_SMF05CT1G | TVS diode array SMF05CT1G, SOT-23-6 package, 5-line transient voltage suppressor | ![IC_SMF05CT1G](images/symbols/IC_SMF05CT1G.png)
D_Generic | Generic LED, 2-pin, through hole or SMD | ![D_Generic](images/symbols/D_Generic.png)
D_SK6812MINI-E | Addressable RGB LED SK6812MINI-E, 3.2×2.8×1.78 mm package | ![D_SK6812MINI-E](images/symbols/D_SK6812MINI-E.png)
J_MJ-4PP-9 | 4-pin stereo audio jack MJ-4PP-9, TRRS compatible | ![J_MJ-4PP-9](images/symbols/J_MJ-4PP-9.png)
R_Generic | Generic resistor, 2-pin, through hole or SMD | ![R_Generic](images/symbols/R_Generic.png)
SW_Encoder_EC11 | Rotary encoder EC11, through hole, 5 pins, with push button | ![SW_Encoder_EC11](images/symbols/SW_Encoder_EC11.png)
SW_Push | Momentary push button, 2 pins, generic footprint | ![SW_Push](images/symbols/SW_Push.png)
SW_Push_45deg | Momentary push button, 2 pins, 45° rotated | ![SW_Push_45deg](images/symbols/SW_Push_45deg.png)
SW_SPDT | SPDT switch (single pole double throw) | ![SW_SPDT](images/symbols/SW_SPDT.png)
U_ProMicro_nRF52840 | Pro Micro nRF52840 microcontroller board symbol | ![U_ProMicro_nRF52840](images/symbols/U_ProMicro_nRF52840.png)
U_ProMicro_RP2040 | Pro Micro RP2040 microcontroller board symbol | ![U_ProMicro_RP2040](images/symbols/U_ProMicro_RP2040.png)
U_XIAO_nRF52840 | Seeed Studio XIAO nRF52840 microcontroller board symbol | ![U_XIAO_nRF52840](images/symbols/U_XIAO_nRF52840.png)
U_Zero_RP2040 | RP2040-Zero microcontroller board symbol | ![U_Zero_RP2040](images/symbols/U_Zero_RP2040.png)