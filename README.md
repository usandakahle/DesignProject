# Micromouse Power Module System

This project is the power module circuit for the EEE3088F design project that provide power to the micromouse system

## Features

-  Boost Converter (3.7V → 5V @ 1.5A)
-  LDO Regulator (5V → 3.3V @ 300mA)
-  Dual H-Bridge Motor Driver (DRV8833 for 4x brushed DC motors)
-  High-Side Load Switches (TPS2HB50-Q1, 2 channels @ 1A each)
-  Physical ON/OFF switch with <30µA shutdown current
-  Small PCB footprint, JLCPCB-ready
-  -All features and components are sourced from JLCPCB (https://jlcpcb.com/parts/all-electronic-components) 

---

##  Design Overview

- Input: 3.7V Li-ion (1S1P)
- Voltage Regulation:
  - Boost: MT3608
  - 3.3V Regulator: AMS1117-3.3 or TLV75533P
- Motor Driver: DRV8833, controls 4 DC motors bidirectionally
- Load Switches:TPS2HB50-Q1 with configurable ILIM resistors
- ON/OFF Circuit: Slide switch + pMOS + NPN low-quiescent design

---



