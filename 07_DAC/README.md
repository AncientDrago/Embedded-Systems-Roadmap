# DAC — Digital to Analog Converter (ATxmega128A1U)

This module covers generating analog voltages using the ATxmega’s built-in 12-bit DAC.

## 📌 What You Will Learn
- DAC basics (resolution, reference, output buffer)
- Configuring single-channel & dual-channel DAC
- Generating static voltages
- Generating waveforms (sine, saw, triangle) using timers
- Using DAC with the event system
- Applications in motor control & analog circuits

## 📁 Folder Contains
- `main.c` → DAC output examples (to be added)
- Notes on DAC registers & reference sources
- Exercises:
  - Generate 0.5V, 1V, 2V outputs  
  - Create a smooth sine wave using a lookup table  
  - DAC + Timer waveform generation  

## 🛠 Hardware Used
- ATxmega128A1U board
- Oscilloscope (recommended)
- RC filters for smoothing (optional)

## 🚀 Next Steps
After this module:
- You can combine ADC + DAC for signal processing tasks  
- You will be ready to implement PID or sensor-actuator loops  
