# Timers & Counters — ATxmega128A1U

This module explains how to configure and use the powerful 16-bit timers on the ATxmega128A1U.

## 📌 What You Will Learn
- Timer basic setup (TC0 / TC1)
- Clock sources & prescalers
- Compare match interrupts
- Overflow interrupts
- Generating periodic events
- Delay generation (non-blocking)
- Introduction to event system

## 📁 Folder Contains
- `main.c` → timer examples (to be added)
- Notes on timer registers and wave generation modes
- Exercises such as:
  - Generate a 1ms system tick  
  - Build a millisecond timer  
  - Implement software PWM  

## 🛠 Hardware Used
- ATxmega128A1U board  
- Logic analyzer or oscilloscope (optional)

## 🚀 Next Steps
After this module:
- You will configure PWM for motor/LED control  
- Then move to serial peripherals (SPI, I2C, USART)

---

# PWM — Pulse Width Modulation (ATxmega128A1U)

This module covers how to use the XMEGA's advanced PWM hardware for LED dimming, motors, control loops, and signal generation.

## 📌 What You Will Learn
- Fast PWM mode configuration
- Single-slope & dual-slope PWM
- Duty cycle control
- Frequency setting using prescalers & TOP value
- PWM on multiple channels (A/B/C/D)
- Inverting vs non-inverting modes

## 📁 Folder Contains
- `main.c` → example PWM programs (to be added)
- Notes on waveform generation registers  
- Exercises:
  - LED brightness fade  
  - Generate a servo motor signal  
  - Multi-channel PWM for motors  

## 🛠 Hardware Used
- ATxmega128A1U board
- LED or servo motor
- Optional oscilloscope for visualization

## 🚀 Next Steps
Mastering PWM leads naturally into:
- Motor control projects  
- PID loops  
- High-resolution timing systems  

