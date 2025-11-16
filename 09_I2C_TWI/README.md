# I²C / TWI — Two-Wire Interface (ATxmega128A1U)

This module teaches how to use the ATxmega's TWI peripheral to communicate with sensors, RTCs, EEPROMs, and other embedded devices.

## 📌 What You Will Learn
- I²C basics (SDA, SCL, pull-ups)
- Master write & read cycles
- Acknowledgment (ACK / NACK)
- Bus speed (Standard / Fast mode)
- Multi-byte register read/write
- Handling bus errors and timeouts
- Debugging I2C with logic analyzer

## 📁 Folder Contains
- `main.c` → I²C master example (to be added)
- Notes on TWI master framework
- Exercises:
  - Read temperature from an I²C sensor (e.g., LM75)  
  - Write/read data to EEPROM  
  - Scan I²C bus for connected devices  

## 🛠 Hardware Used
- ATxmega128A1U board
- Any I²C sensor or EEPROM
- 4.7k pull-up resistors (if needed)

## 🚀 Next Steps
After this module:
- UART will feel much simpler  
- You can build multi-sensor data fusion systems  
