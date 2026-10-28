# Arduino-Uno-Traffic-Light

A beginner-friendly Arduino project built and simulated in Tinkercad that simulates a standard intersection traffic light system using LEDs and current-limiting resistors.

---

## Features
* **Traffic Light Sequence:** Cycles automatically through Red, Yellow, and Green states.
* **Hardware Protection:** Includes 200 ohm resistors on each LED channel to safely limit current and prevent component damage.
* **Virtual Prototyping:** Tested and verified via Tinkercad Circuits before hardware deployment.

---

## Components Used
* **Microcontroller:** Arduino Uno
* **Output Devices:** 
  * Red LED
  * Yellow/Amber LED
  * Green LED
* **Passives:** 3 x 200 ohm resistors
* **Connections:** Hook-up wires and common ground bus

---

## Circuit Connections

| Component | Arduino Pin | Resistor | Notes |
| :--- | :--- | :--- | :--- |
| **Red LED** | Digital Pin 0 | 200 ohm | Anode connected via resistor to Pin 0 |
| **Yellow LED** | Digital Pin 1 | 200 ohm | Anode connected via resistor to Pin 1 |
| **Green LED** | Digital Pin 2 | 200 ohm | Anode connected via resistor to Pin 2 |
| **Cathodes** | GND | — | Common ground rail connected to Arduino GND |
