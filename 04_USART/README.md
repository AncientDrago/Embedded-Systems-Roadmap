# USART — Serial Communication (ATxmega128A1U)

This module explains how to configure UART/USART for debugging, communication with PCs, modules, and other microcontrollers.

## 📌 What You Will Learn
- USART basics (TX, RX, baud rate, frame format)
- Baud rate calculation on XMEGA
- Transmit & receive bytes
- Interrupt-based UART
- Simple command parser over serial
- Using USB-to-Serial converters (FT232 / CH340)
- Debugging techniques

## 📁 Folder Contains
- `main.c` → UART TX/RX examples (to be added)
- Notes on BAUDCTRL and CTRLA/CTRLB registers
- Exercises:
  - Send sensor values over serial  
  - Build a mini serial terminal (echo)  
  - Implement a simple CLI command interface  

## 🛠 Hardware Used
- ATxmega128A1U board  
- USB-UART module or onboard UART connection  
- Serial terminal (CoolTerm, PuTTY, etc.)

## 🚀 Next Steps
After USART:
- You can integrate UART debug prints into every project  
- You will be ready for FreeRTOS or real-time task scheduling  
