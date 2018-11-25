EESchema Schematic File Version 4
LIBS:neil_scope3-cache
EELAYER 29 0
EELAYER END
$Descr A4 11693 8268
encoding utf-8
Sheet 1 4
Title "Neil Scope 3"
Date "2018-11-19"
Rev ""
Comp "http://hobby-research.at.ua/publ/razrabotki/izmerenija/neil_scope_3/4-1-0-42"
Comment1 ""
Comment2 ""
Comment3 ""
Comment4 ""
$EndDescr
$Comp
L CPLD_Altera:EPM570T144 U6
U 1 1 5BF2A8CC
P 2250 4050
F 0 "U6" H 2250 7531 50  0000 C CNN
F 1 "EPM570T144C5N" H 2250 7440 50  0000 C CNN
F 2 "Package_QFP:LQFP-144_20x20mm_P0.5mm" H 2850 800 50  0001 L CNN
F 3 "https://www.altera.com/content/dam/altera-www/global/en_US/pdfs/literature/hb/max2/max2_mii5v1.pdf" H 2250 4050 50  0001 C CNN
	1    2250 4050
	1    0    0    -1  
$EndComp
Text GLabel 10350 3600 2    50   Input ~ 0
PWMB
Text GLabel 10350 3500 2    50   Input ~ 0
PWMA
Text GLabel 10350 4450 2    50   Input ~ 0
ON_B
Text GLabel 10350 4550 2    50   Input ~ 0
ON_A
$Comp
L imm_lib:C CX1
U 1 1 5BF3A628
P 6950 1200
F 0 "CX1" V 6698 1200 50  0000 C CNN
F 1 "20pF" V 6789 1200 50  0000 C CNN
F 2 "Capacitor_SMD:C_0402_1005Metric" V 6800 1150 50  0001 C CNN
F 3 "" H 6950 1200 50  0001 C CNN
	1    6950 1200
	0    1    1    0   
$EndComp
$Comp
L imm_lib:C CX2
U 1 1 5BF3AE05
P 6800 900
F 0 "CX2" V 6548 900 50  0000 C CNN
F 1 "20pF" V 6639 900 50  0000 C CNN
F 2 "Capacitor_SMD:C_0402_1005Metric" V 6650 850 50  0001 C CNN
F 3 "" H 6800 900 50  0001 C CNN
	1    6800 900 
	0    1    1    0   
$EndComp
$Comp
L Device:Crystal X1
U 1 1 5BF3B37B
P 7200 1050
F 0 "X1" V 7154 1181 50  0000 L CNN
F 1 "10MHz" V 7245 1181 50  0000 L CNN
F 2 "Crystal:Crystal_SMD_3215-2Pin_3.2x1.5mm" H 7200 1050 50  0001 C CNN
F 3 "~" H 7200 1050 50  0001 C CNN
	1    7200 1050
	0    1    1    0   
$EndComp
Text GLabel 10400 5350 0    50   Input ~ 0
Host_Active
Text GLabel 10350 3700 2    50   Input ~ 0
Q0
Text GLabel 10350 3800 2    50   Input ~ 0
Q1
Text GLabel 10350 3900 2    50   Input ~ 0
Q2
Text GLabel 10350 4000 2    50   Input ~ 0
Q3
Text GLabel 10350 4100 2    50   Input ~ 0
Q4
Text GLabel 10350 4200 2    50   Input ~ 0
Q5
Text GLabel 7700 2600 0    50   Input ~ 0
Q6
Text GLabel 7700 2500 0    50   Input ~ 0
Q7
$Comp
L Memory_EEPROM:24LC64 U21
U 1 1 5BF60A5E
P 7700 5650
F 0 "U21" H 7700 6131 50  0000 C CNN
F 1 "24LC64" H 7700 6040 50  0000 C CNN
F 2 "Package_SO:SOIC-8_3.9x4.9mm_P1.27mm" H 7700 5650 50  0001 C CNN
F 3 "http://ww1.microchip.com/downloads/en/DeviceDoc/21189f.pdf" H 7700 5650 50  0001 C CNN
	1    7700 5650
	1    0    0    -1  
$EndComp
Wire Wire Line
	7300 5550 7300 5650
Wire Wire Line
	7300 5950 7700 5950
Connection ~ 7300 5650
Wire Wire Line
	7300 5650 7300 5750
Connection ~ 7300 5750
Wire Wire Line
	7300 5750 7300 5950
$Comp
L SparkFun-Aesthetics:DGND #GND0107
U 1 1 5BF62373
P 7700 6050
F 0 "#GND0107" H 7700 6050 50  0001 L BNN
F 1 "DGND" H 7700 5976 50  0000 C CNN
F 2 "" H 7700 6050 50  0001 C CNN
F 3 "" H 7700 6050 50  0001 C CNN
	1    7700 6050
	1    0    0    -1  
$EndComp
Connection ~ 7700 5950
$Comp
L imm_lib:C C48
U 1 1 5BF62728
P 6950 5500
F 0 "C48" H 6835 5454 50  0000 R CNN
F 1 "100nF" H 6835 5545 50  0000 R CNN
F 2 "Capacitor_SMD:C_0402_1005Metric" V 6800 5450 50  0001 C CNN
F 3 "" H 6950 5500 50  0001 C CNN
	1    6950 5500
	-1   0    0    1   
$EndComp
Wire Wire Line
	7700 5350 6950 5350
Wire Wire Line
	6950 5650 6950 5950
Wire Wire Line
	6950 5950 7300 5950
Connection ~ 7300 5950
Wire Wire Line
	8100 5750 8100 5950
Wire Wire Line
	8100 5950 7700 5950
$Comp
L imm_lib:R R76
U 1 1 5BF67330
P 8400 5350
F 0 "R76" H 8330 5304 50  0000 R CNN
F 1 "10k" H 8330 5395 50  0000 R CNN
F 2 "Resistor_SMD:R_0402_1005Metric" V 8300 5400 50  0001 C CNN
F 3 "" H 8400 5450 50  0001 C CNN
	1    8400 5350
	-1   0    0    1   
$EndComp
$Comp
L imm_lib:R R77
U 1 1 5BF68656
P 8100 5350
F 0 "R77" H 8030 5304 50  0000 R CNN
F 1 "10k" H 8030 5395 50  0000 R CNN
F 2 "Resistor_SMD:R_0402_1005Metric" V 8000 5400 50  0001 C CNN
F 3 "" H 8100 5450 50  0001 C CNN
	1    8100 5350
	-1   0    0    1   
$EndComp
Wire Wire Line
	8100 5500 8100 5550
Wire Wire Line
	8100 5550 8450 5550
Connection ~ 8100 5550
Wire Wire Line
	8100 5650 8400 5650
Wire Wire Line
	8400 5500 8400 5650
Connection ~ 8400 5650
Wire Wire Line
	8400 5650 8450 5650
Wire Wire Line
	8400 5200 8100 5200
Wire Wire Line
	7950 5200 7950 5350
Wire Wire Line
	7950 5350 7700 5350
Connection ~ 8100 5200
Wire Wire Line
	8100 5200 7950 5200
Connection ~ 7700 5350
$Comp
L imm_lib:CY7C1041DV33-10ZSXI U5
U 1 1 5BF7B2E5
P 5500 5500
F 0 "U5" H 5500 5725 50  0000 C CNN
F 1 "CY7C1041DV33-10ZSXI" H 5500 5634 50  0000 C CNN
F 2 "Package_SO:TSOP-II-44_10.16x18.41mm_P0.8mm" H 5500 5750 50  0001 C CNN
F 3 "" H 5500 5750 50  0001 C CNN
	1    5500 5500
	1    0    0    -1  
$EndComp
$Comp
L Device:R_Pack04 SR2
U 1 1 5BF7E753
P 4900 6300
F 0 "SR2" V 4483 6300 50  0001 C CNN
F 1 "22" V 4574 6300 50  0001 C CNN
F 2 "Resistor_SMD:R_Array_Convex_4x0402" V 5175 6300 50  0001 C CNN
F 3 "~" H 4900 6300 50  0001 C CNN
	1    4900 6300
	0    1    1    0   
$EndComp
$Comp
L Device:R_Pack04 SR6
U 1 1 5BF81171
P 6100 6800
F 0 "SR6" V 5683 6800 50  0001 C CNN
F 1 "22" V 5774 6800 50  0001 C CNN
F 2 "Resistor_SMD:R_Array_Convex_4x0402" V 6375 6800 50  0001 C CNN
F 3 "~" H 6100 6800 50  0001 C CNN
	1    6100 6800
	0    1    -1   0   
$EndComp
$Comp
L Device:R_Pack04 SR1
U 1 1 5BF821D1
P 4900 5800
F 0 "SR1" V 4483 5800 50  0001 C CNN
F 1 "22" V 4574 5800 50  0001 C CNN
F 2 "Resistor_SMD:R_Array_Convex_4x0402" V 5175 5800 50  0001 C CNN
F 3 "~" H 4900 5800 50  0001 C CNN
	1    4900 5800
	0    1    1    0   
$EndComp
$Comp
L Device:R_Pack04 SR4
U 1 1 5BF84B07
P 4900 7400
F 0 "SR4" V 4483 7400 50  0001 C CNN
F 1 "22" V 4574 7400 50  0001 C CNN
F 2 "Resistor_SMD:R_Array_Convex_4x0402" V 5175 7400 50  0001 C CNN
F 3 "~" H 4900 7400 50  0001 C CNN
	1    4900 7400
	0    1    1    0   
$EndComp
$Comp
L Device:R_Pack04 SR5
U 1 1 5BF852EC
P 6100 7300
F 0 "SR5" V 5683 7300 50  0001 C CNN
F 1 "22" V 5774 7300 50  0001 C CNN
F 2 "Resistor_SMD:R_Array_Convex_4x0402" V 6375 7300 50  0001 C CNN
F 3 "~" H 6100 7300 50  0001 C CNN
	1    6100 7300
	0    1    -1   0   
$EndComp
Wire Wire Line
	5150 6400 5100 6400
Wire Wire Line
	5150 6300 5100 6300
Wire Wire Line
	5150 6200 5100 6200
Wire Wire Line
	5150 6100 5100 6100
Wire Wire Line
	5150 5900 5100 5900
Wire Wire Line
	5150 5800 5100 5800
Wire Wire Line
	5150 5700 5100 5700
Wire Wire Line
	5150 5600 5100 5600
Wire Wire Line
	5150 7200 5100 7200
Wire Wire Line
	5150 7300 5100 7300
Wire Wire Line
	5150 7400 5100 7400
Wire Wire Line
	5150 7500 5100 7500
$Comp
L Device:R_Pack04 SR7
U 1 1 5BFADC78
P 6100 6200
F 0 "SR7" V 5683 6200 50  0001 C CNN
F 1 "22" V 5774 6200 50  0001 C CNN
F 2 "Resistor_SMD:R_Array_Convex_4x0402" V 6375 6200 50  0001 C CNN
F 3 "~" H 6100 6200 50  0001 C CNN
	1    6100 6200
	0    1    -1   0   
$EndComp
$Comp
L Device:R_Pack04 SR8
U 1 1 5BFC019B
P 6100 5600
F 0 "SR8" V 5683 5600 50  0001 C CNN
F 1 "22" V 5774 5600 50  0001 C CNN
F 2 "Resistor_SMD:R_Array_Convex_4x0402" V 6375 5600 50  0001 C CNN
F 3 "~" H 6100 5600 50  0001 C CNN
	1    6100 5600
	0    1    -1   0   
$EndComp
Wire Wire Line
	5900 6100 5850 6100
Wire Wire Line
	5900 6200 5850 6200
Wire Wire Line
	5900 6300 5850 6300
Wire Wire Line
	5900 6400 5850 6400
Wire Wire Line
	5900 6700 5850 6700
Wire Wire Line
	5900 6800 5850 6800
Wire Wire Line
	5900 6900 5850 6900
Wire Wire Line
	5900 7000 5850 7000
Wire Wire Line
	5850 7200 5900 7200
Wire Wire Line
	5850 7300 5900 7300
Wire Wire Line
	5850 7400 5900 7400
Wire Wire Line
	5850 7500 5900 7500
Text GLabel 4700 5500 0    50   Input ~ 0
A0
Text GLabel 4700 5600 0    50   Input ~ 0
A1
Text GLabel 4700 5700 0    50   Input ~ 0
A2
Text GLabel 4700 5800 0    50   Input ~ 0
A3
Text GLabel 4700 5900 0    50   Input ~ 0
A4
Text GLabel 4700 7200 0    50   Input ~ 0
A5
Text GLabel 4700 7300 0    50   Input ~ 0
A6
Text GLabel 4700 7400 0    50   Input ~ 0
A7
Text GLabel 4700 7500 0    50   Input ~ 0
A8
Text GLabel 4700 7600 0    50   Input ~ 0
A9
Text GLabel 6300 7600 2    50   Input ~ 0
A10
Text GLabel 6300 7500 2    50   Input ~ 0
A11
Text GLabel 6300 7400 2    50   Input ~ 0
A12
Text GLabel 6300 7300 2    50   Input ~ 0
A13
Text GLabel 6300 7200 2    50   Input ~ 0
A14
Text GLabel 6300 5700 2    50   Input ~ 0
A15
Text GLabel 6300 5600 2    50   Input ~ 0
A16
Text GLabel 6300 5500 2    50   Input ~ 0
A17
Text GLabel 4700 6100 0    50   Input ~ 0
D0
Text GLabel 4700 6200 0    50   Input ~ 0
D1
Text GLabel 4700 6300 0    50   Input ~ 0
D2
Text GLabel 4700 6400 0    50   Input ~ 0
D3
$Comp
L Device:R_Pack04 SR3
U 1 1 5BFE1640
P 4900 6900
F 0 "SR3" V 4483 6900 50  0001 C CNN
F 1 "22" V 4574 6900 50  0001 C CNN
F 2 "Resistor_SMD:R_Array_Convex_4x0402" V 5175 6900 50  0001 C CNN
F 3 "~" H 4900 6900 50  0001 C CNN
	1    4900 6900
	0    1    1    0   
$EndComp
Text GLabel 4700 6700 0    50   Input ~ 0
D4
Text GLabel 4700 6800 0    50   Input ~ 0
D5
Text GLabel 4700 6900 0    50   Input ~ 0
D6
Text GLabel 4700 7000 0    50   Input ~ 0
D7
Text GLabel 6300 7000 2    50   Input ~ 0
D8
Text GLabel 6300 6900 2    50   Input ~ 0
D9
Text GLabel 6300 6800 2    50   Input ~ 0
D10
Text GLabel 6300 6700 2    50   Input ~ 0
D11
Text GLabel 6300 6400 2    50   Input ~ 0
D12
Text GLabel 6300 6300 2    50   Input ~ 0
D13
Text GLabel 6300 6200 2    50   Input ~ 0
D14
Text GLabel 6300 6100 2    50   Input ~ 0
D15
Wire Wire Line
	5150 7000 5100 7000
Wire Wire Line
	5150 6900 5100 6900
Wire Wire Line
	5150 6800 5100 6800
Wire Wire Line
	5150 6700 5100 6700
Wire Wire Line
	5900 5500 5850 5500
Wire Wire Line
	5900 5600 5850 5600
Wire Wire Line
	5900 5700 5850 5700
Wire Wire Line
	5900 5800 5850 5800
Wire Wire Line
	5850 5900 5850 6000
Connection ~ 5850 6000
Text GLabel 6250 6000 2    50   Input ~ 0
CLK_S
Wire Wire Line
	5900 5900 6250 5900
Text GLabel 6250 5900 2    50   Input ~ 0
O_E
Text GLabel 6300 5800 2    50   Input ~ 0
OE_S-
Text GLabel 5150 6000 0    50   Input ~ 0
CE_S-
$Comp
L imm_lib:R R11
U 1 1 5BF522A4
P 6100 6000
F 0 "R11" V 5893 6000 50  0000 C CNN
F 1 "33" V 5984 6000 50  0000 C CNN
F 2 "Resistor_SMD:R_0402_1005Metric" V 6000 6050 50  0001 C CNN
F 3 "" H 6100 6100 50  0001 C CNN
	1    6100 6000
	0    1    1    0   
$EndComp
Wire Wire Line
	5850 6000 5950 6000
$Comp
L imm_lib:R R30
U 1 1 5BF564FB
P 4900 5500
F 0 "R30" V 4693 5500 50  0000 C CNN
F 1 "22" V 4784 5500 50  0000 C CNN
F 2 "Resistor_SMD:R_0402_1005Metric" V 4800 5550 50  0001 C CNN
F 3 "" H 4900 5600 50  0001 C CNN
	1    4900 5500
	0    1    1    0   
$EndComp
Wire Wire Line
	5150 5500 5050 5500
Wire Wire Line
	4750 5500 4700 5500
$Comp
L imm_lib:R R6
U 1 1 5BF5E18E
P 4900 7600
F 0 "R6" V 5015 7600 50  0000 C CNN
F 1 "22" V 5106 7600 50  0000 C CNN
F 2 "Resistor_SMD:R_0402_1005Metric" V 4800 7650 50  0001 C CNN
F 3 "" H 4900 7700 50  0001 C CNN
	1    4900 7600
	0    1    1    0   
$EndComp
$Comp
L imm_lib:R R7
U 1 1 5BF5EAED
P 6100 7600
F 0 "R7" V 6215 7600 50  0000 C CNN
F 1 "22" V 6306 7600 50  0000 C CNN
F 2 "Resistor_SMD:R_0402_1005Metric" V 6000 7650 50  0001 C CNN
F 3 "" H 6100 7700 50  0001 C CNN
	1    6100 7600
	0    1    1    0   
$EndComp
Wire Wire Line
	5150 7600 5050 7600
Wire Wire Line
	4750 7600 4700 7600
Wire Wire Line
	6300 7600 6250 7600
$Comp
L imm_lib:R R16
U 1 1 5BF6F566
P 4450 7100
F 0 "R16" V 4243 7100 50  0000 C CNN
F 1 "33" V 4334 7100 50  0000 C CNN
F 2 "Resistor_SMD:R_0402_1005Metric" V 4350 7150 50  0001 C CNN
F 3 "" H 4450 7200 50  0001 C CNN
	1    4450 7100
	0    1    1    0   
$EndComp
Wire Wire Line
	4600 7100 5150 7100
Text GLabel 4300 7100 0    50   Input ~ 0
WE_S-
$Comp
L imm_lib:C C29
U 1 1 5BF7DBCB
P 6600 6750
F 0 "C29" H 6485 6704 50  0000 R CNN
F 1 "100nF" H 6485 6795 50  0000 R CNN
F 2 "Capacitor_SMD:C_0402_1005Metric" V 6450 6700 50  0001 C CNN
F 3 "" H 6600 6750 50  0001 C CNN
	1    6600 6750
	-1   0    0    1   
$EndComp
Text GLabel 6600 6600 2    50   Input ~ 0
+2.7V
Wire Wire Line
	5850 6600 6600 6600
Wire Wire Line
	6500 6500 6500 6900
Wire Wire Line
	6500 6900 6600 6900
$Comp
L SparkFun-Aesthetics:DGND #GND0108
U 1 1 5BF87A09
P 6600 7000
F 0 "#GND0108" H 6600 7000 50  0001 L BNN
F 1 "DGND" H 6600 6926 50  0000 C CNN
F 2 "" H 6600 7000 50  0001 C CNN
F 3 "" H 6600 7000 50  0001 C CNN
	1    6600 7000
	1    0    0    -1  
$EndComp
$Comp
L imm_lib:C C28
U 1 1 5BF87DC9
P 4200 6650
F 0 "C28" H 4085 6604 50  0000 R CNN
F 1 "100nF" H 4085 6695 50  0000 R CNN
F 2 "Capacitor_SMD:C_0402_1005Metric" V 4050 6600 50  0001 C CNN
F 3 "" H 4200 6650 50  0001 C CNN
	1    4200 6650
	-1   0    0    1   
$EndComp
Wire Wire Line
	4200 6500 5150 6500
Wire Wire Line
	4200 6800 4550 6800
Wire Wire Line
	4550 6800 4550 6600
Wire Wire Line
	4550 6600 5150 6600
$Comp
L SparkFun-Aesthetics:DGND #GND0109
U 1 1 5BF92160
P 4200 6900
F 0 "#GND0109" H 4200 6900 50  0001 L BNN
F 1 "DGND" H 4200 6826 50  0000 C CNN
F 2 "" H 4200 6900 50  0001 C CNN
F 3 "" H 4200 6900 50  0001 C CNN
	1    4200 6900
	1    0    0    -1  
$EndComp
Connection ~ 4200 6800
Text GLabel 4200 6500 0    50   Input ~ 0
+2.7V
$Sheet
S 10250 5850 900  550 
U 5BFA3848
F0 "AD9288BST" 50
F1 "AD9288BST.sch" 50
$EndSheet
Text GLabel 150  1650 0    50   Input ~ 0
IO_0
Text GLabel 150  1750 0    50   Input ~ 0
IO_1
Text GLabel 150  1850 0    50   Input ~ 0
IO_2
Text GLabel 150  1950 0    50   Input ~ 0
IO_3
Text GLabel 150  2050 0    50   Input ~ 0
IO_4
Text GLabel 150  2150 0    50   Input ~ 0
IO_5
$Comp
L imm_lib:R R10
U 1 1 5BFD1B56
P 900 2700
F 0 "R10" V 693 2700 50  0000 C CNN
F 1 "33" V 784 2700 50  0000 C CNN
F 2 "Resistor_SMD:R_0402_1005Metric" V 800 2750 50  0001 C CNN
F 3 "" H 900 2800 50  0001 C CNN
	1    900  2700
	-1   0    0    1   
$EndComp
Text GLabel 900  2850 3    50   Input ~ 0
CLK_100
Wire Wire Line
	1050 2550 900  2550
Text GLabel 150  2250 0    50   Input ~ 0
IO_6
Text GLabel 150  2350 0    50   Input ~ 0
IO_7
Text GLabel 1050 3550 0    50   Input ~ 0
OSC_EN
Text GLabel 750  6650 0    50   Input ~ 0
TMS
Text GLabel 750  6750 0    50   Input ~ 0
TDI
Text GLabel 750  6850 0    50   Input ~ 0
TCK
Text GLabel 750  6950 0    50   Input ~ 0
TDO
Text GLabel 1050 3650 0    50   Input ~ 0
A10
Text GLabel 1050 3750 0    50   Input ~ 0
A11
Text GLabel 1050 3850 0    50   Input ~ 0
A12
Text GLabel 1050 3950 0    50   Input ~ 0
A13
Text GLabel 1050 4050 0    50   Input ~ 0
A14
Text GLabel 1050 4150 0    50   Input ~ 0
D8
Text GLabel 1050 4250 0    50   Input ~ 0
D9
Text GLabel 1050 4350 0    50   Input ~ 0
D10
Text GLabel 1050 4450 0    50   Input ~ 0
D11
Text GLabel 1050 4550 0    50   Input ~ 0
A9
Text GLabel 1050 4650 0    50   Input ~ 0
A8
Text GLabel 1050 4750 0    50   Input ~ 0
A7
Text GLabel 1050 4850 0    50   Input ~ 0
A6
Text GLabel 1050 4950 0    50   Input ~ 0
A5
Text GLabel 1050 5050 0    50   Input ~ 0
WE_S-
Text GLabel 1050 5150 0    50   Input ~ 0
D7
Text GLabel 1050 5250 0    50   Input ~ 0
D6
Text GLabel 1050 5350 0    50   Input ~ 0
D5
Text GLabel 1050 5450 0    50   Input ~ 0
D4
Text GLabel 1050 5550 0    50   Input ~ 0
D3
Text GLabel 1050 5650 0    50   Input ~ 0
D2
Text GLabel 1050 5750 0    50   Input ~ 0
D1
Text GLabel 1050 5850 0    50   Input ~ 0
D0
Text GLabel 3450 1350 2    50   Input ~ 0
CLK_S
Text GLabel 1050 5950 0    50   Input ~ 0
CE_S-
Text GLabel 1050 6050 0    50   Input ~ 0
A4
Text GLabel 1050 6150 0    50   Input ~ 0
A3
Text GLabel 1050 6250 0    50   Input ~ 0
A2
Text GLabel 1050 6350 0    50   Input ~ 0
A1
Text GLabel 1050 6450 0    50   Input ~ 0
A0
Wire Wire Line
	2750 7350 2650 7350
Connection ~ 1750 7350
Wire Wire Line
	1750 7350 1650 7350
Connection ~ 1850 7350
Wire Wire Line
	1850 7350 1750 7350
Connection ~ 1950 7350
Wire Wire Line
	1950 7350 1850 7350
Connection ~ 2050 7350
Wire Wire Line
	2050 7350 1950 7350
Connection ~ 2150 7350
Wire Wire Line
	2150 7350 2050 7350
Connection ~ 2250 7350
Wire Wire Line
	2250 7350 2150 7350
Connection ~ 2350 7350
Wire Wire Line
	2350 7350 2250 7350
Connection ~ 2450 7350
Wire Wire Line
	2450 7350 2350 7350
Connection ~ 2550 7350
Wire Wire Line
	2550 7350 2450 7350
Connection ~ 2650 7350
Wire Wire Line
	2650 7350 2550 7350
Text GLabel 1650 7350 0    50   Input ~ 0
DGND
Wire Wire Line
	2750 750  2650 750 
Connection ~ 1750 750 
Wire Wire Line
	1750 750  1650 750 
Connection ~ 1850 750 
Wire Wire Line
	1850 750  1750 750 
Connection ~ 1950 750 
Wire Wire Line
	1950 750  1850 750 
Connection ~ 2050 750 
Wire Wire Line
	2050 750  1950 750 
Connection ~ 2150 750 
Wire Wire Line
	2150 750  2050 750 
Connection ~ 2250 750 
Wire Wire Line
	2250 750  2150 750 
Connection ~ 2350 750 
Wire Wire Line
	2350 750  2250 750 
Connection ~ 2450 750 
Wire Wire Line
	2450 750  2350 750 
Connection ~ 2550 750 
Wire Wire Line
	2550 750  2450 750 
Connection ~ 2650 750 
Wire Wire Line
	2650 750  2550 750 
Text GLabel 3450 6250 2    50   Input ~ 0
AD8
Text GLabel 3450 6350 2    50   Input ~ 0
AD9
Text GLabel 3450 6450 2    50   Input ~ 0
AD10
Text GLabel 3450 6550 2    50   Input ~ 0
AD11
Text GLabel 3450 6650 2    50   Input ~ 0
AD12
Text GLabel 3450 6750 2    50   Input ~ 0
AD13
Text GLabel 3450 6850 2    50   Input ~ 0
AD14
Text GLabel 3450 6950 2    50   Input ~ 0
AD15
Text GLabel 3450 5450 2    50   Input ~ 0
AD0
Text GLabel 3450 5350 2    50   Input ~ 0
AD1
Text GLabel 3450 5250 2    50   Input ~ 0
AD2
Text GLabel 3450 5150 2    50   Input ~ 0
AD3
Text GLabel 3450 5050 2    50   Input ~ 0
AD4
Text GLabel 3450 4950 2    50   Input ~ 0
AD5
Text GLabel 3450 4850 2    50   Input ~ 0
AD6
Text GLabel 3450 4750 2    50   Input ~ 0
AD7
Text GLabel 3450 5950 2    50   Input ~ 0
BCLK
Text GLabel 3450 5750 2    50   Input ~ 0
ACLK
Text GLabel 3450 4250 2    50   Input ~ 0
WR_SRAM_RDY
Text GLabel 3450 3850 2    50   Input ~ 0
Q7
Text GLabel 3450 3750 2    50   Input ~ 0
Q6
Text GLabel 3450 3650 2    50   Input ~ 0
Q5
Text GLabel 3450 3550 2    50   Input ~ 0
Q4
Text GLabel 3450 3450 2    50   Input ~ 0
Q3
Text GLabel 3450 3350 2    50   Input ~ 0
Q2
Text GLabel 3450 4150 2    50   Input ~ 0
WR
Text GLabel 3450 4050 2    50   Input ~ 0
RS
Text GLabel 3450 3950 2    50   Input ~ 0
RD
Text GLabel 3450 3250 2    50   Input ~ 0
Q1
Text GLabel 3450 3150 2    50   Input ~ 0
Q0
Text GLabel 3450 1750 2    50   Input ~ 0
A17
Text GLabel 3450 1650 2    50   Input ~ 0
A16
Text GLabel 3450 1550 2    50   Input ~ 0
A15
Text GLabel 3450 1450 2    50   Input ~ 0
OE_S-
Text GLabel 3450 1250 2    50   Input ~ 0
D15
Text GLabel 3450 1150 2    50   Input ~ 0
D14
Text GLabel 3450 1050 2    50   Input ~ 0
D13
Text GLabel 1050 6550 0    50   Input ~ 0
D12
$Sheet
S 9150 5800 1000 600 
U 5BFF3A54
F0 "analog" 50
F1 "analog.sch" 50
$EndSheet
$Sheet
S 8250 5800 800  600 
U 5C135D23
F0 "led" 50
F1 "led.sch" 50
$EndSheet
Wire Wire Line
	5900 5900 5900 5800
Connection ~ 5900 5800
Wire Wire Line
	5850 7600 5950 7600
Wire Wire Line
	5850 6500 6500 6500
Connection ~ 6600 6900
$Comp
L opendous:LPC175x U1
U 1 1 5BF9D93F
P 9300 2950
F 0 "U1" H 9025 5203 60  0000 C CNN
F 1 "LPC175x" H 9025 5097 60  0000 C CNN
F 2 "Package_QFP:LQFP-80_12x12mm_P0.5mm" H 9300 2950 60  0001 C CNN
F 3 "" H 9300 2950 60  0001 C CNN
	1    9300 2950
	1    0    0    -1  
$EndComp
$Comp
L dk_Transistors-Bipolar-BJT-Single:MMBT3904WT1G Q6
U 1 1 5C01F7B6
P 10600 5350
F 0 "Q6" H 10788 5403 60  0000 L CNN
F 1 "MMBT3904WT1G" H 10788 5297 60  0000 L CNN
F 2 "Package_TO_SOT_SMD:SOT-323_SC-70" H 10800 5550 60  0001 L CNN
F 3 "http://www.onsemi.com/pub/Collateral/MMBT3904WT1-D.PDF" H 10800 5650 60  0001 L CNN
F 4 "MMBT3904WT1GOSCT-ND" H 10800 5750 60  0001 L CNN "Digi-Key_PN"
F 5 "MMBT3904WT1G" H 10800 5850 60  0001 L CNN "MPN"
F 6 "Discrete Semiconductor Products" H 10800 5950 60  0001 L CNN "Category"
F 7 "Transistors - Bipolar (BJT) - Single" H 10800 6050 60  0001 L CNN "Family"
F 8 "http://www.onsemi.com/pub/Collateral/MMBT3904WT1-D.PDF" H 10800 6150 60  0001 L CNN "DK_Datasheet_Link"
F 9 "/product-detail/en/on-semiconductor/MMBT3904WT1G/MMBT3904WT1GOSCT-ND/1139816" H 10800 6250 60  0001 L CNN "DK_Detail_Page"
F 10 "TRANS NPN 40V 0.2A SOT323" H 10800 6350 60  0001 L CNN "Description"
F 11 "ON Semiconductor" H 10800 6450 60  0001 L CNN "Manufacturer"
F 12 "Active" H 10800 6550 60  0001 L CNN "Status"
	1    10600 5350
	1    0    0    -1  
$EndComp
$Comp
L SparkFun-Aesthetics:DGND #GND03
U 1 1 5C020C82
P 10700 5650
F 0 "#GND03" H 10700 5650 50  0001 L BNN
F 1 "DGND" H 10700 5576 50  0000 C CNN
F 2 "" H 10700 5650 50  0001 C CNN
F 3 "" H 10700 5650 50  0001 C CNN
	1    10700 5650
	1    0    0    -1  
$EndComp
Wire Wire Line
	10350 4350 10700 4350
$Comp
L imm_lib:R R26
U 1 1 5C0454A8
P 10850 4350
F 0 "R26" V 10643 4350 50  0000 C CNN
F 1 "10k" V 10734 4350 50  0000 C CNN
F 2 "Resistor_SMD:R_0402_1005Metric" V 10750 4400 50  0001 C CNN
F 3 "" H 10850 4450 50  0001 C CNN
	1    10850 4350
	0    1    1    0   
$EndComp
Connection ~ 10700 4350
Text GLabel 11000 4350 3    50   Input ~ 0
+2.7V
Wire Wire Line
	7200 900  6950 900 
Wire Wire Line
	7100 1200 7200 1200
Connection ~ 7200 1200
Wire Wire Line
	7200 1200 7700 1200
Wire Wire Line
	7700 1100 7700 900 
Wire Wire Line
	7700 900  7200 900 
Connection ~ 7200 900 
Wire Wire Line
	6800 1200 6650 1200
Wire Wire Line
	6650 1200 6650 900 
$Comp
L imm_lib:C C9
U 1 1 5C064F76
P 6650 1350
F 0 "C9" H 6535 1304 50  0000 R CNN
F 1 "100nF" H 6535 1395 50  0000 R CNN
F 2 "Capacitor_SMD:C_0402_1005Metric" V 6500 1300 50  0001 C CNN
F 3 "" H 6650 1350 50  0001 C CNN
	1    6650 1350
	-1   0    0    1   
$EndComp
Connection ~ 6650 1200
Wire Wire Line
	7700 1650 6650 1650
$Comp
L imm_lib:R R9
U 1 1 5C06D13F
P 6500 1650
F 0 "R9" V 6293 1650 50  0000 C CNN
F 1 "10k" V 6384 1650 50  0000 C CNN
F 2 "Resistor_SMD:R_0402_1005Metric" V 6400 1700 50  0001 C CNN
F 3 "" H 6500 1750 50  0001 C CNN
	1    6500 1650
	0    1    1    0   
$EndComp
Connection ~ 6650 1650
Wire Wire Line
	6650 1500 6650 1650
Text GLabel 6350 1650 1    50   Input ~ 0
+2.7V
$Comp
L SparkFun-Aesthetics:DGND #GND01
U 1 1 5C086FEB
P 7700 5100
F 0 "#GND01" H 7700 5100 50  0001 L BNN
F 1 "DGND" H 7700 5026 50  0000 C CNN
F 2 "" H 7700 5100 50  0001 C CNN
F 3 "" H 7700 5100 50  0001 C CNN
	1    7700 5100
	1    0    0    -1  
$EndComp
Text GLabel 7250 4700 0    50   Input ~ 0
+2.7V
$Comp
L imm_lib:C C10
U 1 1 5C0875FC
P 7250 4850
F 0 "C10" H 7135 4804 50  0000 R CNN
F 1 "100nF" H 7135 4895 50  0000 R CNN
F 2 "Capacitor_SMD:C_0402_1005Metric" V 7100 4800 50  0001 C CNN
F 3 "" H 7250 4850 50  0001 C CNN
	1    7250 4850
	-1   0    0    1   
$EndComp
Wire Wire Line
	7700 4700 7250 4700
Wire Wire Line
	7700 4800 7700 5000
Wire Wire Line
	7250 5000 7700 5000
Connection ~ 7700 5000
Wire Wire Line
	8350 5000 8450 5000
Connection ~ 8450 5000
Wire Wire Line
	8450 5000 8550 5000
Connection ~ 8550 5000
Wire Wire Line
	8550 5000 8650 5000
Connection ~ 8650 5000
Wire Wire Line
	8650 5000 8750 5000
Connection ~ 8750 5000
Wire Wire Line
	8750 5000 8850 5000
Connection ~ 8850 5000
Wire Wire Line
	8850 5000 8950 5000
Wire Wire Line
	8350 5000 7700 5000
Connection ~ 8350 5000
Wire Wire Line
	10700 4350 10700 5150
Text GLabel 10350 4800 2    50   Input ~ 0
+2.7V
$Comp
L imm_lib:C C36
U 1 1 5C0AD30D
P 10350 4950
F 0 "C36" H 10235 4904 50  0000 R CNN
F 1 "100nF" H 10235 4995 50  0000 R CNN
F 2 "Capacitor_SMD:C_0402_1005Metric" V 10200 4900 50  0001 C CNN
F 3 "" H 10350 4950 50  0001 C CNN
	1    10350 4950
	-1   0    0    1   
$EndComp
Wire Wire Line
	8950 5100 8950 5000
Connection ~ 8950 5000
Wire Wire Line
	8950 5100 10350 5100
Text GLabel 9050 900  2    50   Input ~ 0
+2.7V
Wire Wire Line
	9050 900  8950 900 
Connection ~ 8550 900 
Wire Wire Line
	8550 900  8450 900 
Connection ~ 8650 900 
Wire Wire Line
	8650 900  8550 900 
Connection ~ 8750 900 
Wire Wire Line
	8750 900  8650 900 
Connection ~ 8850 900 
Wire Wire Line
	8850 900  8750 900 
Connection ~ 8950 900 
Wire Wire Line
	8950 900  8850 900 
$Comp
L imm_lib:C C35
U 1 1 5C0BE2B8
P 8450 750
F 0 "C35" H 8335 704 50  0000 R CNN
F 1 "100nF" H 8335 795 50  0000 R CNN
F 2 "Capacitor_SMD:C_0402_1005Metric" V 8300 700 50  0001 C CNN
F 3 "" H 8450 750 50  0001 C CNN
	1    8450 750 
	-1   0    0    1   
$EndComp
Connection ~ 8450 900 
$Comp
L imm_lib:C C11
U 1 1 5C0BE9E3
P 8000 750
F 0 "C11" H 7885 704 50  0000 R CNN
F 1 "100nF" H 7885 795 50  0000 R CNN
F 2 "Capacitor_SMD:C_0402_1005Metric" V 7850 700 50  0001 C CNN
F 3 "" H 8000 750 50  0001 C CNN
	1    8000 750 
	-1   0    0    1   
$EndComp
Wire Wire Line
	8450 900  8000 900 
Wire Wire Line
	8450 600  8000 600 
$Comp
L SparkFun-Aesthetics:DGND #GND02
U 1 1 5C0CB004
P 7900 600
F 0 "#GND02" H 7900 600 50  0001 L BNN
F 1 "DGND" V 7900 571 50  0000 R CNN
F 2 "" H 7900 600 50  0001 C CNN
F 3 "" H 7900 600 50  0001 C CNN
	1    7900 600 
	0    1    1    0   
$EndComp
Connection ~ 8000 600 
Text GLabel 7700 3400 0    50   Input ~ 0
ENC_B
Text GLabel 7700 3300 0    50   Input ~ 0
ENCA2
Text GLabel 7700 3200 0    50   Input ~ 0
ENCA1
Text GLabel 7700 3100 0    50   Input ~ 0
ENCA0
Text GLabel 7700 3000 0    50   Input ~ 0
ENCBUT0
Text GLabel 7700 2900 0    50   Input ~ 0
ENCBUT1
Text GLabel 7700 2800 0    50   Input ~ 0
ENCBUT2
Text GLabel 7700 2700 0    50   Input ~ 0
ENCBUT3
Text GLabel 7700 2300 0    50   Input ~ 0
LD0
Text GLabel 10350 2450 2    50   Input ~ 0
LD1
Text GLabel 10350 2550 2    50   Input ~ 0
LD2
Text GLabel 10350 2650 2    50   Input ~ 0
LD3
Text GLabel 10350 2750 2    50   Input ~ 0
LD4
Text GLabel 10350 2850 2    50   Input ~ 0
LD5
Text GLabel 10350 2950 2    50   Input ~ 0
LD6
Text GLabel 10350 3050 2    50   Input ~ 0
LD7
Text GLabel 10350 3150 2    50   Input ~ 0
LRES
Text GLabel 10350 3250 2    50   Input ~ 0
WR_573
Text GLabel 10350 3350 2    50   Input ~ 0
LCS-
Text GLabel 7700 2200 0    50   Input ~ 0
LRS-
Text GLabel 10350 1200 2    50   Input ~ 0
BackLight
Text GLabel 10350 1300 2    50   Input ~ 0
U_TX
Text GLabel 10350 1400 2    50   Input ~ 0
U_RX
Text GLabel 10350 1500 2    50   Input ~ 0
ENC_IRQ
Text GLabel 10350 1600 2    50   Input ~ 0
SPI_SCK
Text GLabel 10350 1700 2    50   Input ~ 0
SPI_CS
Text GLabel 10350 1800 2    50   Input ~ 0
SPI_MOSI
Text GLabel 10350 1900 2    50   Input ~ 0
SDA
Text GLabel 10350 2000 2    50   Input ~ 0
SCL
Text GLabel 7700 3600 0    50   Input ~ 0
WR
Text GLabel 7700 3700 0    50   Input ~ 0
RD
Text GLabel 7700 3800 0    50   Input ~ 0
RS
Text GLabel 7700 3900 0    50   Input ~ 0
WR_SRAM_RDY
Text GLabel 10350 2200 2    50   Input ~ 0
BATT_MON
Text GLabel 10350 2300 2    50   Input ~ 0
BUZZER
Text GLabel 7700 1950 0    50   Input ~ 0
LWR-
Text GLabel 7700 2050 0    50   Input ~ 0
LRD-
Text GLabel 8450 5550 2    50   Input ~ 0
SDA
Text GLabel 8450 5650 2    50   Input ~ 0
SCL
$Comp
L SparkFun-Aesthetics:DGND #GND0101
U 1 1 5C1041DC
P 6550 1200
F 0 "#GND0101" H 6550 1200 50  0001 L BNN
F 1 "DGND" V 6550 1171 50  0000 R CNN
F 2 "" H 6550 1200 50  0001 C CNN
F 3 "" H 6550 1200 50  0001 C CNN
	1    6550 1200
	0    1    1    0   
$EndComp
Text GLabel 1050 1050 0    50   Input ~ 0
PWM_B
Text GLabel 950  1250 0    50   Input ~ 0
SPIMOSI
Text GLabel 950  1350 0    50   Input ~ 0
SPICS
Text GLabel 950  1450 0    50   Input ~ 0
SPISCK
Wire Wire Line
	750  6650 1000 6650
Wire Wire Line
	1050 6750 950  6750
Wire Wire Line
	1050 6850 900  6850
Wire Wire Line
	1050 6950 850  6950
$Comp
L imm_lib:R R27
U 1 1 5C167383
P 1250 7450
F 0 "R27" V 1043 7450 50  0000 C CNN
F 1 "1k" V 1134 7450 50  0000 C CNN
F 2 "Resistor_SMD:R_0402_1005Metric" V 1150 7500 50  0001 C CNN
F 3 "" H 1250 7550 50  0001 C CNN
	1    1250 7450
	0    1    1    0   
$EndComp
$Comp
L imm_lib:R R31
U 1 1 5C167843
P 1250 7550
F 0 "R31" V 1043 7550 50  0000 C CNN
F 1 "1k" V 1134 7550 50  0000 C CNN
F 2 "Resistor_SMD:R_0402_1005Metric" V 1150 7600 50  0001 C CNN
F 3 "" H 1250 7650 50  0001 C CNN
	1    1250 7550
	0    1    1    0   
$EndComp
$Comp
L imm_lib:R R36
U 1 1 5C1679D2
P 1250 7650
F 0 "R36" V 1043 7650 50  0000 C CNN
F 1 "1k" V 1134 7650 50  0000 C CNN
F 2 "Resistor_SMD:R_0402_1005Metric" V 1150 7700 50  0001 C CNN
F 3 "" H 1250 7750 50  0001 C CNN
	1    1250 7650
	0    1    1    0   
$EndComp
$Comp
L imm_lib:R R42
U 1 1 5C167B46
P 1250 7750
F 0 "R42" V 1043 7750 50  0000 C CNN
F 1 "1k" V 1134 7750 50  0000 C CNN
F 2 "Resistor_SMD:R_0402_1005Metric" V 1150 7800 50  0001 C CNN
F 3 "" H 1250 7850 50  0001 C CNN
	1    1250 7750
	0    1    1    0   
$EndComp
Wire Wire Line
	1000 6650 1000 7450
Wire Wire Line
	1000 7450 1100 7450
Connection ~ 1000 6650
Wire Wire Line
	1000 6650 1050 6650
Wire Wire Line
	950  6750 950  7550
Wire Wire Line
	950  7550 1100 7550
Connection ~ 950  6750
Wire Wire Line
	950  6750 750  6750
Wire Wire Line
	900  6850 900  7650
Wire Wire Line
	900  7650 1100 7650
Connection ~ 900  6850
Wire Wire Line
	900  6850 750  6850
Wire Wire Line
	850  6950 850  7750
Wire Wire Line
	850  7750 1100 7750
Connection ~ 850  6950
Wire Wire Line
	850  6950 750  6950
Wire Wire Line
	1400 7650 1950 7650
Wire Wire Line
	1950 7650 1950 7350
Wire Wire Line
	1400 7750 1550 7750
Wire Wire Line
	1550 7750 1550 7550
Wire Wire Line
	1550 7550 1400 7550
Wire Wire Line
	1400 7450 1550 7450
Wire Wire Line
	1550 7450 1550 7550
Connection ~ 1550 7550
Text GLabel 1550 7550 2    50   Input ~ 0
+2.7V
Text GLabel 3550 2250 2    50   Input ~ 0
SPI_SCK
Text GLabel 3550 2350 2    50   Input ~ 0
SPI_CS
Text GLabel 3550 2750 2    50   Input ~ 0
SPI_MOSI
Text GLabel 3450 4550 2    50   Input ~ 0
PWM_A
Text GLabel 1650 750  0    50   Input ~ 0
+2.7V
Text GLabel 5600 750  0    50   Input ~ 0
DGND
$Comp
L SparkFun-Aesthetics:DGND #GND0102
U 1 1 5C231D3A
P 5700 750
F 0 "#GND0102" H 5700 750 50  0001 L BNN
F 1 "DGND" V 5700 721 50  0000 R CNN
F 2 "" H 5700 750 50  0001 C CNN
F 3 "" H 5700 750 50  0001 C CNN
	1    5700 750 
	0    -1   -1   0   
$EndComp
Text GLabel 6950 5350 0    50   Input ~ 0
+2.7V
Text GLabel 3450 2950 2    50   Input ~ 0
PWMA
Text GLabel 3450 3050 2    50   Input ~ 0
PWMB
$Comp
L connectors:HEADER-1x10 J1
U 1 1 5C288F58
P 600 2100
F 0 "J1" H 567 2757 60  0000 C CNB
F 1 "HEADER-1x10" H 567 2666 40  0000 C CNN
F 2 "Connector_PinSocket_2.54mm:PinSocket_2x05_P2.54mm_Vertical" H 600 2100 60  0001 C CNN
F 3 "" H 600 2100 60  0001 C CNN
F 4 "-" H 550 2750 40  0001 L BNN "Part"
F 5 "Connector" H 550 2850 40  0001 L BNN "Family"
	1    600  2100
	-1   0    0    1   
$EndComp
Wire Wire Line
	1050 1650 750  1650
Wire Wire Line
	1050 1750 750  1750
Wire Wire Line
	1050 1850 750  1850
Wire Wire Line
	1050 1950 750  1950
Wire Wire Line
	1050 2050 750  2050
Wire Wire Line
	1050 2150 750  2150
Wire Wire Line
	1050 2250 750  2250
Wire Wire Line
	1050 2350 750  2350
Text GLabel 750  2550 3    50   Input ~ 0
DGND
$Comp
L connectors:HEADER-1x06 J2
U 1 1 5C30FD5D
P 3650 7400
F 0 "J2" H 3778 7436 60  0000 L CNB
F 1 "HEADER-1x06" H 3778 7345 40  0000 L CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_1x06_P2.54mm_Vertical" H 3650 7400 60  0001 C CNN
F 3 "" H 3650 7400 60  0001 C CNN
F 4 "-" H 3600 7850 40  0001 L BNN "Part"
F 5 "Connector" H 3600 7950 40  0001 L BNN "Family"
	1    3650 7400
	1    0    0    -1  
$EndComp
Text GLabel 3500 7250 0    50   Input ~ 0
TMS
Text GLabel 3500 7350 0    50   Input ~ 0
TDI
Text GLabel 3500 7450 0    50   Input ~ 0
TCK
Text GLabel 3500 7550 0    50   Input ~ 0
TDO
Text GLabel 3500 7150 0    50   Input ~ 0
+2.7V
Text GLabel 3500 7650 0    50   Input ~ 0
DGND
Text GLabel 4600 5200 0    50   Input ~ 0
DGND
Text GLabel 5850 2500 2    50   Input ~ 0
LD1
Text GLabel 5850 1700 2    50   Input ~ 0
LD2
Text GLabel 5850 1800 2    50   Input ~ 0
LD3
Text GLabel 5850 1900 2    50   Input ~ 0
LD4
Text GLabel 5850 2000 2    50   Input ~ 0
LD5
Text GLabel 5850 2100 2    50   Input ~ 0
LD6
Text GLabel 5850 2200 2    50   Input ~ 0
LD7
Text GLabel 4900 1600 0    50   Input ~ 0
LRES
Text GLabel 4900 1700 0    50   Input ~ 0
LCS-
Text GLabel 5850 2400 2    50   Input ~ 0
LD0
Text GLabel 4900 1800 0    50   Input ~ 0
LRS-
Text GLabel 4900 1900 0    50   Input ~ 0
LWR-
Text GLabel 4900 2000 0    50   Input ~ 0
LRD-
$Comp
L imm_lib:3,97_TFT_st7793_arduino_uno2 D1
U 1 1 5BFA6F17
P 5550 1900
F 0 "D1" H 5375 2525 50  0000 C CNN
F 1 "3,97_TFT_st7793_arduino_uno" H 5375 2434 50  0000 C CNN
F 2 "imm:3,97_TFT_st7793_arduino_uno2" H 5550 2650 50  0001 C CNN
F 3 "" H 5550 2650 50  0001 C CNN
	1    5550 1900
	1    0    0    -1  
$EndComp
Text GLabel 4900 2300 0    50   Input ~ 0
DGND
Text GLabel 4900 2600 0    50   Input ~ 0
+2.7V
Wire Wire Line
	750  2550 750  2450
$EndSCHEMATC
