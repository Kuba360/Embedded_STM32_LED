# STM32F303RE - LED & Joystick Controller

Firmware for the **NUCLEO-F303RE** board developed in **STM32CubeIDE** using **HAL**. It controls 4 LEDs and a 5-pin analog joystick using an State Machine.

##  Hardware Setup
- **MCU:** NUCLEO-F303RE 
- **Input:** 5-pin Analog Joystick (VRx, VRy, SW)
- **Output:** 4x LEDs with 220 Ω current-limiting resistors


## SM Modes (Toggled via SW Button)

1. **State 0:** All LEDs OFF
2. **State 1:** All LEDs ON
3. **State 2:** Alternating Blinking Pattern
4. **State 3:** Chasing LED Wave
5. **State 4:** Joystick Directional Control:
   - **Right** : Green LED
   - **Left** : Yellow LED
   - **Up** : Red LED
   - **Down** : Blue LED

