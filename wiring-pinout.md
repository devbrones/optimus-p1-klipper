# Pinout of the wiring of OP1



| Label | Label | Pins | Gauge |
|-------|-------|------|-------|
| A     | E     ||
| B     |       |       |10x0.3mm2


C:10x0.3mm2
E:14x0.2mm2
D:8x0.2mm2

D & E -> Head (D8, e14) AC
C -> Z axis, dual 



C - Z: 
Left stepper (5,6) (9,10) 
Right stepper (3,4) (1,2) 
NC (7,8)

B - Y: 
Stepper (3,4) (1,2)
Stepper (7,8) (9,10)
Endstop (5,6)
Grå kabel > Gul=blå | Grön=grön | Vit=röd | Brun=Svart |

A - X:
Endstop (5,6)
Stepper (1,2)(3,4)

Bed AC RED BLACK Phase 1 Green white phase 2

Add voltage monitoring and dc ok via pi gpio from MW psu
Kolla Y endstop
USB webbcam

ADXL Wiring
Ethernet
Twisted pair for: 
GND+MISO  | Brown+WhiteBrown 
3.3V+MOSI | Orange+WhiteOrange
SCLK+CS   | Blue+WhiteBlue





extruder:
14 pin
Thermistor: 2 pins

Fans: 
 -Extruder cooler fan: 2 pins
 -Blowers x2: 2pins 

Bltouch: 5 pins (SERVO vcc gnd sig) (zstop + -) 

Accelerometer: 6 pins (vcc gnd sda scl sdo cs)


pinout 14:
1  EXCOOL P
2  EXCOOL N
3  BLOW P
4  BLOW N
5  Z STOP -
6  Z STOP +
7  SERVO SIG
8  SERVO VCC
9  SERVO GND
10 THERMISTOR A
11 THERMISTOR A
12 UNUSED
13 UNUSED
14 UNUSED


8 pin
Heat cart: 2/4 pins
Extruder Stepper 4 pins

pinout 8:
1 HEAT-LEFT P
2 HEAT-LEFT N
3 HEAT-RIGHT P
4 HEAT-RIGHT N
5 EXTR-MOT black
6 EXTR-MOT green
7 EXTR-MOT blue
8 EXTR-MOT red









