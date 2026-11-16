# Blinking-Heart-LED


## Introduction
The purpose of this project is to create and design a blinking LED circuit in the shape of a heart.  This was done by testing Integrated 
Circuits (IC) and basic electronic circuit design to achieve desired effects. The final version of this product was implemented and designed on 
a PCB to fulfill the visible physical requirements per the designer. No coding was required for this project as the fulfillment of the desired 
requirements only needed electronic circuit logic via a 555 Integrated Circuit timer. Software used to complete this project included KiCad and 
TinkerCad. Production of the PCB was completed by JLCPCB and electronic components were soldered in house.

## Hardware Specification
### NE555 IC
The overall circuit is designed around the Texas Instrument NE55 Timer IC. This timer is used for multiple applications and the one used for 
this circuit is using its Astable feature.  Pinout for the IC timer is located in Figure 1.
<p align='center'>
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/0e3ee712-0254-41e0-96fc-471543c7e3ce" />
</p>

<div align='center'>
  
**Figure 1: Texas Instrument NE555 Timer**

</div>

The Astable feature of the NE555 allows for an input voltage of 4.5-16V and creates a periodic on and off waveform.  This feature is used to 
create Pulse-Width-Modulation(PWM) which can be used to blink LEDs on and off or used for motor applications.  Sample waveform provided from 
the datasheet can be seen in Figure 2. This PWM feature is accomplished by having two comparator logic gates that feed into the main circuitry 
of the IC which will read voltage levels and act as an automatic switching logic gate which will output a 0V or high voltage output.  

<p align='center'>
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/2abc60de-dbc7-43ed-8340-76c2fbfc8740" />
</p>

<div align='center'>
  
**Figure 2: Sample Waveform Graph**

</div>

