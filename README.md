# NodeMCU-ESP-32S-3-Axis-CNC-Controller

## 3-Axis CNC Controller using Trinamic TMC5160 drivers.

### Runs the GRBL-ESP32 firmware by bdring found here https://github.com/bdring/Grbl_Esp32/tree/TMCStepper

###### Board Specifications:

- 24V DC nominal motor/board supply voltage 
  - Working Range
    - 18V DC (min)
    - 36V DC (max)
- Based on ESP32 MCU
- 3 x stepper drivers (TMC5160) to suit 3-axis machines
- Multiple spindle control options 
  - 3.3V PWM output
  - 0-5V analog DC output
  - 0-10V analog DC output
  - 3.3V spindle enable binary output (works with 5v logic VFD binary inputs as well)
- Z Probe input (3.3V logic level)
- All screw terminals are 5.08mm pitch for reliability and durability
- On-board micro SD card support
- Spindle Coolant Relay (active when spindle is enabled) with LED indicator
- Tool/Cutting Coolant Relay (active with grbl mist output is enabled) with LED indicator
- 3 x power LED's (3.3V, 5V and 24V)
