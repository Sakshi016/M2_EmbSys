# Components used and its connection
# COMPONENTS

## LCD DISPLAY
 ![Screenshot (349)](https://user-images.githubusercontent.com/98878326/157265248-e85f3de5-02d1-4e23-8001-2b9ce88b250a.png)

## Ultrasonic sensor
![Ultrasonic sensor](https://user-images.githubusercontent.com/98878326/157266475-efa41645-11cd-457c-94ac-e51231d28ef6.png)

## Breadboard

 ![breadboard](https://user-images.githubusercontent.com/98878326/157266462-8311028d-65bb-4b7b-ab14-4b010ea12151.png)
 
 ## SWITCHES
 ![slide switch](https://user-images.githubusercontent.com/98878326/157267997-783415b4-3ce3-4062-8fac-25fc197a1335.png)
![tactile switch](https://user-images.githubusercontent.com/98878326/157268002-cd54b4cf-3da2-4dce-8deb-dc0593250530.png)

## ARDIUNO UNO 
![arduino uno](https://user-images.githubusercontent.com/98878326/157268003-5a4d197d-abfd-458a-b790-28b40d8c74da.png)

## RESISTOR
![resistor](https://user-images.githubusercontent.com/98878326/157268005-64caf86d-23a7-4078-b430-acbcf6816a31.png)

# CONNECTIONS

VSS - GND

VCC - 5v

VEE/VO - Potentiometer Wiper Pin (Centre Pin). Potentiometer other two end pins to - One to Arduino Uno's 5v and and other to its Gnd

RS - D2

RW - Gnd

E - D3

D0 - Gnd/No Connection

D1 - Gnd/No Connection

D2 - Gnd/No Connection

D3 - Gnd/No Connection

We are not connecting LCD Screen's (D0, D1, D2, D3) pins because we are using 4 bit mode to display the text.

D4 - D4 (Arduino Uno/Nano/Mega/Any Other Board)

D5 - D5 (Arduino Uno/Nano/Mega/Any Other Board)

D6 - D6 (Arduino Uno/Nano/Mega/Any Other Board)

D7 - D7 (Arduino Uno/Nano/Mega/Any Other Board)

Led Anode [ Short Form - A] / (LED +) - 5v (Arduino Uno)

RelayToArduinoUno:-

Connect Relay modules IN (Signal/INPUT) to Arduino Uno's D12 pin.

Relay's Gnd to Arduino Gnd. Its 5v pin to Arduino's 5v

MODE(AUTO/MANUAL)SwitchToArduino:-

Connect the switch's one end to Gnd of Arduino and the other end to D11 of Arduino Uno.

PUMP(ON/OFF|DISTANCESET)SwitchToArduino:-

Connect the push button switch's one end to Gnd of Arduino and the other to its D10 pin.


