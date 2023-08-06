# stm32-breakout
# Schematic of circuit
![schematic](https://github.com/anilv8/stm32-breakout/assets/81171588/8445107f-5110-459b-b439-da9741d3c9e9)

## ERC Result
![erc](https://github.com/anilv8/stm32-breakout/assets/81171588/4f607688-4df1-40fc-8f57-0b0d042e2cb1)

# PCB Board
### Front Copper
![front-copper](https://github.com/anilv8/stm32-breakout/assets/81171588/2142a545-ab11-4a31-911d-0da8583d3923)

### Back copper
![back-copper](https://github.com/anilv8/stm32-breakout/assets/81171588/91bb4385-3f7e-4180-aa88-70f4b447f939)

## DRC Result
![Uploading drc.png…]()

## 3D view of PCB
### Front:
![3d-view-front](https://github.com/anilv8/stm32-breakout/assets/81171588/0642e436-ceb5-44d9-8c0c-d62065305a7b)

### Back:
![3d-view-back](https://github.com/anilv8/stm32-breakout/assets/81171588/2b35ccdf-2b97-4286-b91e-79b459aad581)

## Gerber
### Front Copper
![gerber-front-copper](https://github.com/anilv8/stm32-breakout/assets/81171588/bb88704a-15db-4c89-b651-2b98400df604)

### Back Copper
![gerber-back-copper](https://github.com/anilv8/stm32-breakout/assets/81171588/3a1349a9-a33a-4f1a-a999-1aae7e2f813d)

# BOM
| Item	| Qty	| Reference(s)	| Value	| LibPart	| Footprint	| Datasheet |
| ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| 1	| 2	| C1, C2 |	1u	| Device:C |	Capacitor_SMD:C_0603_1608Metric |	~ |
| 2	| 1	| C3 |	4u7	| Device:C	| Capacitor_SMD:C_0603_1608Metric |	~ |
| 3 |	5 |	C4, C5, C6, C7, C9 |	100n |	Device:C	| Capacitor_SMD:C_0402_1005Metric |	~ |
| 4 |	1 |	C8 |	1u |	Device:C |	Capacitor_SMD:C_0402_1005Metric	| ~ |
| 5	| 2	| C10, C11	| 30p	| Device:C	| Capacitor_SMD:C_0402_1005Metric	| ~ |
| 6 |	1 |	D1	| GREEN |	Device:LED_Small |	LED_SMD:LED_0603_1608Metric |	~ |
| 7	| 1	| D2 |	BLUE	| Device:LED_Small	| LED_SMD:LED_0603_1608Metric |	~ |
| 8 |	1	| FB1	| 100R	| Device:FerriteBead	| Inductor_SMD:L_0805_2012Metric |	~ |
| 9 |	4	| H1, H2, H3, H4 |	MountingHole |	Mechanical:MountingHole	MountingHole:MountingHole_2.2mm_M2 |	~ |
| 10 | 1 |	J1 |	USB_B_Micro	| Connector:USB_B_Micro |	Connector_USB:USB_Micro-B_Wuerth_629105150521	| ~ |
| 11	| 2	| J2, J3 |	Conn_01x15	| Connector_Generic:Conn_01x15	| Connector_PinHeader_2.54mm:PinHeader_1x15_P2.54mm_Vertical	| ~ |
| 12 |	1	| JP1	| SolderJumper_2_Open |	Jumper:SolderJumper_2_Open	| Jumper:SolderJumper-2_P1.3mm_Open_Pad1.0x1.5mm |	~ |
| 13	| 1	| L1	| 27n |	Device:L	| Inductor_SMD:L_0402_1005Metric | ~ |
| 14 |	2 |	R1, R3	| 1k5 |	Device:R |	Resistor_SMD:R_0603_1608Metric	| ~ |
| 15	| 1	| R2	| 10k	| Device:R	| Resistor_SMD:R_0402_1005Metric	| ~ |
| 16 |	1 |	R4	| 1k5	| Device:R |	Resistor_SMD:R_0402_1005Metric |	~ |
| 17 | 1	| U1	| XC6206P333MR	| Regulator_Linear:XC6206PxxxMR	| Package_TO_SOT_SMD:SOT-23-3	| https://www.torexsemi.com/file/xc6206/XC6206.pdf |
| 18	| 1 | U2	| STM32F103C8Tx	| MCU_ST_STM32F1:STM32F103C8Tx	| Package_QFP:LQFP-48_7x7mm_P0.5mm |	https://www.st.com/resource/en/datasheet/stm32f103c8.pdf |
| 19 |	1|	Y1 |	8MHz	| Device:Crystal_Small	| Crystal:Crystal_SMD_5032-2Pin_5.0x3.2mm	| ~ |

