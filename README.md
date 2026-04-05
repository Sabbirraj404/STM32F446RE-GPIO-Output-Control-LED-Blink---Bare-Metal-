# STM32 LED Blink (Bare Metal - GPIO)

This project demonstrates how to blink an LED using STM32F4 (STM32F446RE) with register-level programming (no HAL/LL). The LED is connected to GPIOA pin PA5.

---

## Features

- Bare-metal (register-level) programming  
- Direct GPIO control  
- No HAL or external libraries  
- Simple delay-based LED blinking  

---

## Working Principle

- Enable GPIOA clock  
- Configure PA5 as output  
- Turn LED ON and OFF using ODR register  
- Use software delay for timing  

---

## Hardware Connections

- LED Anode → PA5  
- LED Cathode → GND (via resistor)  

---

## Code Explanation

### Clock Enable
- Enable AHB1 clock for GPIOA  

### GPIO Configuration
- Set PA5 as output mode  

### LED Control
- Set bit → LED ON  
- Clear bit → LED OFF  

---

## Output

- LED connected to PA5 blinks continuously  

---

## Requirements

- STM32F446RE (Nucleo/Discovery)  
- LED + Resistor  
- ST-Link Debugger  
- Keil / STM32CubeIDE  

---

## Learning Outcomes

- GPIO register configuration  
- Bitwise operations  
- Embedded C basics  
- Bare-metal programming  

