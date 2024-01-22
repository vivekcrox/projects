# 🔥🚒 Fire Alarm System by Interfacing Arduino with Temperature & Gas Sensor using TinkerCad          
  <img src="https://github.com/vivekcrox/projects/assets/133307528/71d7a613-bbbd-444a-9cba-227f2fb93fac" height="200">

## ❄ Overview

This project entails the creation of a fire alarm circuit using temperature and gas sensors, interfaced with Arduino on TinkerCad simulation software. The simulation environment allows for thorough testing before physical implementation, mitigating potential damage risks.

## 🛠 Hardware Requirements

1. **Arduino UNO Board:**
   
   <img src="https://github.com/vivekcrox/projects/assets/133307528/b26edd4e-e4f1-4c5a-bd35-23811b9ea8ab" height="100">
   
   - Microcontroller for processing sensor inputs and providing desired outputs.
  
3. **TMP-36 Temperature Sensor:**

   <img src="https://github.com/vivekcrox/projects/assets/133307528/45979346-fad4-4430-8881-2b782efde4fe" height="100">
   
   - Provides analog output proportional to instantaneous temperature.

5. **Gas Sensor (MQ2):**

    <img src="https://github.com/vivekcrox/projects/assets/133307528/3c3fdb72-2fcf-402c-a7ae-aa764696e856" height="100">
    
   - Measures gas concentration and detects smoke; generates output in terms of voltage.
   - Produces a corresponding potential difference by changing the resistance of the material inside the sensor, measured as output voltage.
   - Detects gas concentration in ppm and outputs an analog value, convertible to digital using Arduino's inbuilt ADC.

7. **Resistors (1k Ohm):**
   
    <img src="https://github.com/vivekcrox/projects/assets/133307528/8fda7879-8d9e-44ad-837e-2f5e0ec69cc8" height="100">
   
   - Passive devices to restrict current flow and divide voltage in the circuit.

9. **Breadboard:**
    
   <img src="https://github.com/vivekcrox/projects/assets/133307528/148d2480-125c-48f3-99a7-a8598d44df18" height="100">

   - Basic component for circuit building, facilitating wired connections.

11. **LED (Light Emitting Diode):**
    
<img src="https://github.com/vivekcrox/projects/assets/133307528/765928d1-1b96-4343-abbf-3c7e47c1cb75" height="100">

   - Semiconductor light source.

11. **Piezo Buzzer:**
    
<img src="https://github.com/vivekcrox/projects/assets/133307528/fdaedd2b-f881-49bf-b311-9b16321c00b3" height="100">

   - Generates beep sound based on input.

11. **Jumper Wires:**
   - Establish connections between different devices in the circuit.

## 👩🏻‍💻 Software Requirement

- **TinkerCad Circuit Simulation Software:**
  - Online simulation software for circuit design, equipped with necessary electrical components.

## ❄ Simulation

- Use TinkerCad to simulate the circuit:
  - Drag components to the circuit screen and connect using jumper wires.
  - Configure wires with corresponding colors.

## 🔧 Circuit Connections

- Connect Arduino's 5V pin to one line and ground to another on the breadboard.
- Connect LM-35 Temperature Sensor: Vs to power, Ground to ground, Vout to Analog pin A1.
- Connect Gas Sensor (MQ2): Power to power, Ground to ground, Analog pin to A0.
- Connect Piezo Buzzer: Ground to ground, Digital pin to PIN 7.
- Connect LED: Cathode to GND pin, Anode through resistor to Digital pin 13.

## ❄ Working

The circuit functions in two parts:

1. **Temperature Sensor:**
   - As temperature increases, voltage rises.
   - LED responds based on programmed conditions

     <img src="https://github.com/vivekcrox/projects/assets/133307528/3b2477e3-dc33-40f2-9006-be0ce20af768" height="300">

2. **Gas Sensor:**
   - Detects gas concentration and smoke; analog output converted to digital using ADC.
   - Activating the Piezo Buzzer.

     <img src="https://github.com/vivekcrox/projects/assets/133307528/387a4f00-5642-4de7-b623-bc9a05f26b14" height="300">

#
## 🏷 Conclusion

This project provides a practical understanding of interfacing sensors with Arduino to create a fire alarm system, emphasizing the importance of simulation for circuit testing and safety assessment.
