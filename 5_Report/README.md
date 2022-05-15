## INTRODUCTION
Driving securely requires high level of visibility. A windshield wiper, also known as a wiper blade, is a device that cleans the front window of a car from snow, ice, washer fluid, rain and water. Wipers are fitted on all heavy motor vehicles, including cars, trucks, rail line locomotives, and some aircraft.  Safety standards for motor vehicles in adverse weather are important even at low speeds, therefore I began developing a wiper control system with arm-based microcontrollers. Rubber blades are mounted to the metal arms, while pivot magnets are mounted to the other ends. This project helps the user in their everyday lives by avoiding accidents and ensuring for secure and healthful travel. Thus, windshild wipers enhance visibility, efficiency, and reliability.
## OBJECTIVE
The main objective of this project is to design wiper control system to enhance visibility, efficiency and reliability. The goal is to prevent the accidents during the rainy season.
# Features
- Ignition key position at ACC: The red LED is ON, if the user button is pressed once and held for 2 secs.
- Ignition key position at lock: The red LED is OFF, on pressing the user button again and hold for 2 secs.
- Wiper ON: On pressing the user button again blue, green, orange LEDs will ON one at a time with the set frequency.
- Wiper OFF: The LED glow pattern stops when there is next press of the user button.
## RESEARCH
This wiper control system application is researched from various sources like google, research papers, youtube etc. After that, I have developed wiper control system using arm based microcontrollers.
## GOAL
- Achieving clear visibility in bad weather condition.
- Reducing accidents
- Ensuring safety with modern mechanism
- To assure the perfect view for safety driving
- To detach rain drops, snow and other debris from the windshield
## SOFTWARE USED
- STM32 CUBE IDE
- QEMO
## COMPONENTS DESCRIPTION
## STM32F407VG
The STM32F407 kit is a high performance microcontroller which has the capability to make it simple for users to create applications. It has an ST-LINK embedded debug tool, an ST- MEMS digital accelerometer, a digital microphone, LEDs, pushbuttons, an audio DAC with integrated class D speaker driver, Ethernet connectivity, an LCD display, USB OTG micro-AB connector and other features have been added to the STM32F4 kit. The STM32F405XX and STM32F407XX families are built around the high perfomance Arm cortex- M4 bit RISC core,which runs at up to 168 MHz.
## SPECIFIC FEATURES OF STM32F407VG MICROCONTROLLER
- Up to 1 Mbyte of flash memory
- Up to 192+4 Kbytes of SRAM
- 512 bytes of OTP memory
- Flexible static memory controller supporting compact flash SRAM, PSRAM, NOR and NAND memories
## USES
- Rain sensing windshield wipers detect moisture on the windshield and activate the wipers to help increase driver visibility
- It helps to reduce the number of accidents caused by the blur windshield
## 4W's And 1H
## Who
- Everyone who needs to drive safely and with a clear view of the road.
## What
- Wiper Control System for vehicles.
## When
- When you realise the necessity of safety management and begin to take responsibility for your own health while driving in adverse weather.
## Where
- This can be utilised in daily life by the user to assess their safety and lead to better outcomes in life while travelling.
## How
- The position of the wiper is indicated by the LED, which returns to its original position after cleaning the windsheet of the vehicle.
## FEATURES
- Lock the car when button is pressed once.
- Unlock the car when button is pressed twice.
- Wiper on and it moves in clock wise direction when the button is pressed thrice.
- Wiper off and it moves in anti clock wise direction when the button is pressed four times.
## SWOT ANALYSIS:
## STRENGTH
- Clear visibility
- Single button can manage all commands
- Wiper does not stop in the middle, it goes to its original position.
- Installation is simple
## WEAKNESS
- Maintenance
- Replacement of wiper is required
## OPPORTUNITIES
- Reducing accidents
## THREATS
- cost
- Replaced by modern technology
## HIGH LEVEL REQUIREMENTS
| RID | DESCRIPTION | STATUS |
| --- | --- | --- |
| HLR1 |	Locking the car | IMPLEMENTED |
| HLR2 |	Triggering the wiper system | IMPLEMENTED |
| HLR3 |	Shutting the wiper system | IMPLEMENTED |
| HLR4 |	Unlocking the car | IMPLEMENTED |
## LOW LEVEL REQUIREMENTS:
| RID |	DESCRIPTION | STATUS |
| --- | --- | --- |
| LLR1 |	Press button once and hold for 2 secs | IMPLEMENTED |
| LLR2 |	Press button twice and hold for 2 secs| IMPLEMENTED |
| LLR3 |	Press button thrice ON blue, green, orange | IMPLEMENTED |
| LLR4 |	Press button four times OFF blue, green, orange  | IMPLEMENTED |
## FLOW CHART
![FLOWCHART](https://user-images.githubusercontent.com/101622270/168106685-a7027ae9-4bc2-4520-9fee-b79776c03cfd.PNG)
## BLOCK DIAGRAM
![Block_diagram](https://user-images.githubusercontent.com/101622270/168106736-40be3039-a57a-40c5-9add-1282e3cf9369.PNG)
## STRUCTURAL DIAGRAM
![structural diagram](https://user-images.githubusercontent.com/101622270/168106870-fa8b3ad1-0277-4bf0-a525-36f0a13328e3.PNG)
## BEHAVIOR DIAGRAM
![behavior diagram](https://user-images.githubusercontent.com/101622270/168106962-3ac18618-f090-45ec-9e95-5a5126ea9c4b.PNG)
## Test Plan
## Table no 1: High level test plan
Test ID | Description | Expected I/P | Expected O/P |
--------|-------------|---------|---------
H_01  | Engine ON | Press button once | Engine will ON |
H_02  | Engine OFF | Press button twice | Engine will OFF |
H_03  | Wiper ON | Press button thrice | Wiper will ON |
H_04  | Wiper OFF | Press buttor four times | Wiper will OFF |
## Table no 2: Low level test plan
Test ID | Description | Expected I/P | Expected O/P |
--------|-------------|---------|---------
L_01  | Check for Engine ON | Press button once | will ON engine |
L_02  | Check for Engine OFF | Press button twice | will OFF engine |
L_03  | Check for Wiper ON | Press button thrice | will ON wiper |
L_04  | Check for Wiper OFF | Press buttor four times | will OFF wiper |
# Engine ON
![Screenshot (1923)](https://user-images.githubusercontent.com/101622270/168479942-f042b9fe-e723-4f4e-8006-c6145795c545.png)
# Engine OFF
![Screenshot (1924)](https://user-images.githubusercontent.com/101622270/168479953-33a428d8-1601-428b-b62c-4434bea84f70.png)


