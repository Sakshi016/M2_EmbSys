# AUTOMATIC PUMP LEVEL CONTROLLER
 
 ## CONTENTS
 
|Sr. no| Title|
|--|--|
|0|Content|
|1|Introduction|
|2| Block Diagram |
|3| Features|
|4|State of art|
|5|Requirements|
|6| SWOT ANALYSIS|
|7| 5 W's and 1H|
|8|Diagrams|
|9|Components used|

# INTRODUCTION

Water Level Controller using Microcontroller will help in automatically controlling the water motor by sensing the water level in a tank.
The Water Level Sensing Section senses the level of water in the tank and sends it to the Receiver Section. Receiver Section is connected to the Controlling Section, which process the received information and produces visual, sound indications and controls the operation of the motor whenever required.

# BLOCK DIAGRAM

![Flow chrt water c](https://user-images.githubusercontent.com/98878326/155835327-cc645385-5126-416c-9789-02cc8731dbc2.png)

# FEATURES

* conserves water
* alerts are sent out as soon as the water level drops.
* saves pump life
* fully automatic
* indicates amount of water
* easy to use


# STATE OF ART AND RESEARCH

*  We need such devices in order to prevent the overflow of water from the tanks.
* detects zone of danger
* compact design
* feature touch keys


# REQUIREMENTS OF PROJECT 
   
   * Arduino Uno
   * 16 x 2 LCD Display
   * Ultrasonic Sensor (HCSR-04)
   * Breadboard
   * Potentiometer (10k)
   * 1k Resistor
   * Relay Module
   * Push Button
   * SPST Switch
   

# SWOT ANALYSIS

![SWOT analysis](https://user-images.githubusercontent.com/98878326/155833060-62e53bbf-dd9e-4ed2-b402-963c7061acf3.png)

# 5 W's & 1H

## WHO
  
   - All the people be it for the domestic use or be it for industrial purpose.
   - Sewer services for office and apartment buildings.
   
## WHAT

   - Resulting into less manual work.


## WHERE
 
  - Hotels, home apartments,factories.
   
## WHY
   
   * Automatically supplies water to elevated tanks and buildings.
   * Outputting alarms for water shortage or water rise in elevated tanks.

## WHEN 

   * To ensure constant reserve of water in storage tank


# HOW

Automatic water level controller switch the motor on whenever the water level drops below a certain level and shuts the motor off when the water rises well above a fixed level.


# COMPONENT DIAGRAM

![component diagram ](https://user-images.githubusercontent.com/98878326/155835228-0069be0f-8c12-4baf-969a-5a138d53d7a1.jpeg)

# FLOW CHART

![flowchart wlc](https://user-images.githubusercontent.com/98878326/155835250-a6eac639-8ed0-4bbc-8a87-b28eb65e1baa.png)



# COMPONENTS USED

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


# TEST PLAN

# HIGH LEVEL TEST PLAN

| Test id | Description      | Expected input | Actual output | Expected output | Passed or Failed |
| ------- | ------| --------------- |---------------|----------|--------|
|  H1     |sensor detection of water overflow        | overflow of water | detects user through alarm|detects user through alarm| Passed |
|  H2     |low,medium,high waterlevel detection       | level of water    | detects user through alarm|detects user through alarm| Passed |




# LOW LEVEL TEST PLAN 

| Test id |Description      | Expected input | Actual output |Expected output| Passed or Failed |      
|-------- |------| --------------- |  -------------|---------|--------|
| L1      |Tank full| Switches motor off | prevents power loss |prevents power loss | Passed |
| L2      | Tank not filled upto a level | Switches motor on |maintains level of water |maintains level of water | Passed|




