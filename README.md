# fly-1

this is a universal platform for flight controllers 


<img width="860" height="597" alt="image" src="https://github.com/user-attachments/assets/cdbb1446-5725-4ed6-82b7-ad51b852a1d0" />


## what it has

uses the stm32 F4 as the main processing unit long with the RP2340 for NAV processing 

includes 
     GPS
     BAROMETER
     MAGNOMETER
     IMU 

  ### power supply

  this can take current from LiPo batterys upto 60v is supported

## BOM 

the full BOM exported by easyeda is present in the fabrication folder you can also see it here

| ID | Name | Designator | Footprint | Quantity | Manufacturer Part | Manufacturer | Supplier | Supplier Part | Price ($) |
| :-- | :-- | :-- | :-- | :-: | :-- | :-- | :-- | :-- | :-: |
| 1 | 33uF | C1 | CAP-SMD_BD10.0-L10.3-W10.3-FD | 1 | EEHZA1K330P | PANASONIC(松下) | LCSC | C128469 | 0.779 |
| 2 | 100nF | C2 | C0805 | 1 | 08053C104KAT2A | Kyocera AVX | LCSC | C167411 | 0.080 |
| 3 | 390pF | C3 | C0402 | 1 | GRM1555C1H391JA01J | muRata(村田) | LCSC | C2168577 | 0.006 |
| 4 | 4.7uF | C7,C8,C9,C19,C38 | C0402 | 5 | TCC0402X5R475M6R3AT | CCTC(三环) | LCSC | C380302 | 0.013 |
| 5 | 100nF | C10,C11,C12,C13,C14,C15,C16,C17,C18,C20,C21,C24,C26,C27,C28,C29,C30,C31,C35 | C0402 | 19 | CL05B104KO5NNNC | SAMSUNG(三星) | LCSC | C1525 | 0.005 |
| 6 | 15pF | C22,C23 | C0402 | 2 | CL05C150JB5NNNC | SAMSUNG(三星) | LCSC | C86285 | 0.005 |
| 7 | 10uF | C25 | C0402 | 1 | GRM155R60J106ME44D | muRata(村田) | LCSC | C76991 | 0.037 |
| 8 | 2.2uF | C32,C33,C34 | C0402 | 3 | CL05A225KO5NQNC | SAMSUNG(三星) | LCSC | C170151 | 0.034 |
| 9 | 12pF | C36,C37 | C0402 | 2 | CC0402JRNPO9BN120 | YAGEO(国巨) | LCSC | C106201 | 0.003 |
| 10 | 68uF | C4,C5,C6 | C2220 | 3 | C5750X5R1A686M230KA | TDK | LCSC | C2182025 | 1.124 |
| 11 | MBRB40250TG | D1 | D2PAK_L9.1-W10.0-P2.54-LS15.3-BR | 1 | MBRB40250TG | onsemi(安森美) | LCSC | C480682 | 9.735 |
| 12 | HX PH254-01-03-Z-L11.5 PCB PIN HEADER | H1 | HDR-TH_3P-P2.54-V-M-1 | 1 | HX PH254-01-03-Z-L11.5 pcb pin header | hanxia(韩下) | LCSC | C52016391 | 0.023 |
| 13 | PZ254V-11-02P | H2 | HDR-TH_2P-P2.54-V-M | 1 | PZ254V-11-02P | XFCN(兴飞) | LCSC | C492401 | 0.017 |
| 14 | 12uH | L1 | IND-SMD_L12.0-W12.0_744771008 | 1 | CDRH127NP-120MC | Sumida(胜美达) | LCSC | C338772 | 0.681 |
| 15 | 3.3uH | L2 | IND-SMD_L2.0-W1.6_AOTA-B201610S3R3-101-T | 1 | AOTA-B201610S3R3-101-T | ABRACON | LCSC | C42411119 | 0.284 |
| 16 | 69.8kΩ | R1 | R0402 | 1 | CRCW040269K8FKED | VISHAY(威世) | LCSC | C4351510 | 0.008 |
| 17 | 0Ω | R5 | R0402 | 1 | ERJ2GE0R00X | PANASONIC(松下) | LCSC | C242160 | 0.005 |
| 18 | 1kΩ | R6 | R0402 | 1 | ERJ2RKF1001X | PANASONIC(松下) | LCSC | C242161 | 0.017 |
| 19 | 22kΩ | U5,U6 | R0402 | 2 | FRC0402J223 TS | FOJAN(富捷) | LCSC | C2906913 | 0.002 |
| 20 | 68kΩ | R2 | R0603 | 1 | RC0603FR-0768KL | YAGEO(国巨) | LCSC | C114633 | 0.002 |
| 21 | 12kΩ | R3 | R0603 | 1 | RC0603FR-0712KL | YAGEO(国巨) | LCSC | C114659 | 0.008 |
| 22 | 33kΩ | R4,R7 | R0603 | 2 | FRC0603F3302TS | FOJAN(富捷) | LCSC | C2907028 | 0.003 |
| 23 | TS-1088-AR02016 | SW1 | SW-SMD_L3.9-W3.0-P4.45 | 1 | TS-1088-AR02016 | XUNPU(讯普) | LCSC | C720477 | 0.056 |
| 24 | RP2350A_C42411118 | U1 | QFN-60_L7.0-W7.0-P0.40-TL-EP3.4 | 1 | RP2350A | Raspberry Pi(树莓派) | LCSC | C42411118 | 1.712 |
| 25 | LMR16030PDDAR | U2 | SOIC-8_L4.9-W3.9-P1.27-LS6.0-BL-EP | 1 | LMR16030PDDAR | TI(德州仪器) | LCSC | C90665 | 0.581 |
| 26 | KF301-5.0-2P | U3 | CONN-TH_P5.00_KF301-5.0-2P | 1 | KF301-5.0-2P | KEFA(科发) | LCSC | C474881 | 0.101 |
| 27 | ST1L05APU33R | U4 | DFN-6_L3.0-W3.0-P0.95-BL-EP-1 | 1 | ST1L05APU33R | ST(意法半导体) | LCSC | C283488 | 1.111 |
| 28 | W25Q128JVSIQTR | U7 | SOIC-8_L5.3-W5.3-P1.27-LS8.0-BL | 1 | W25Q128JVSIQ | Winbond(华邦) | LCSC | C97521 | 2.549 |
| 29 | 12MHz | U8 | CRYSTAL-SMD_4P-L3.2-W2.5-BL | 1 | ABM8-272-T3 | ABRACON | LCSC | C20625731 | 0.296 |
| 30 | 8MHz | U11 | CRYSTAL-SMD_4P-L3.2-W2.5-BL | 1 | FL0800011Q | DIODES(美台) | LCSC | C1986585 | 0.741 |
| 31 | ICM-45686 | U9 | LGA-14_L3.0-W2.5-P0.50-TL | 1 | ICM-45686 | TDK InvenSense(应美盛) | LCSC | C22459454 | 11.838 |
| 32 | HDGCPH-PZ01-10 | U12,U13,U14,U18 | HDR-TH_10P-P2.54-V-M_1 | 4 | HDGCPH-PZ01-10 | HDGC(华德共创) | LCSC | C19190976 | 0.055 |
| 33 | MAX-M10S-00B | U15 | SMD-18_L10.1-W9.7-P1.10-TL_SKG09F | 1 | MAX-M10S-00B | U-BLOX(优北罗) | LCSC | C4153167 | 10.546 |
| 34 | IST8310_C2683055 | U16 | LGA-16_L3.0-W3.0-P0.50-BL_SQ | 1 | IST8310 | iSentek(爱盛科技) | LCSC | C2683055 | 3.768 |
| 35 | BMP280 | U17 | LGA-8_L2.5-W2.0-P0.65_AMP6127 | 1 | BMP280 | Bosch(博世) | LCSC | C83291 | 12.885 |
| 36 | MICROXNJ | USB1,USB2 | MICRO-USB-SMD_MICROXNJ_1 | 2 | MicroXNJ | SHOU HAN(首韩) | LCSC | C404969 | 0.041 |
| 37 | STM32F405RGT6 | U10 | LQFP-64_L10.0-W10.0-P0.50-LS12.0-BL | 1 | STM32F405RGT6 | ST(意法半导体) | LCSC | C15742 | 6.950 |
