## Hi, I'm Tuấn (Ho Anh Tuan)

Final-year Electronics & Telecommunications student (High-Quality Program) at the
University of Science, VNU-HCM. I work on **embedded firmware for STM32** and
**digital IC design** from RTL to layout.

**Looking for a 3–6 month internship** in Embedded Systems or Digital IC Design
in Ho Chi Minh City.

### Projects

| Project | What it is | Evidence |
|---|---|---|
| [smart-door-lock-stm32](https://github.com/imtuaz/smart-door-lock-stm32) | STM32F103 door lock: RFID (RC522, SPI) + keypad PIN, servo latch, I2C LCD, ESP8266 email alerts, card list stored in flash | Course project, Microcontrollers, 2025; app logic unit-tested on PC |
| [mpu6050-tilt](https://github.com/imtuaz/mpu6050-tilt) | MPU6050 over I2C, roll/pitch with a complementary filter at 100 Hz, hardware-independent driver | `make test`: 24 unit tests with a mocked I2C bus; not yet run on hardware |
| [protocol-analyzer](https://github.com/imtuaz/protocol-analyzer) | Software logic analyzer in C99: decodes UART, SPI, I2C, CAN, flags protocol and timing errors, HTML/SVG report, reads PulseView CSV | `make test`: 117 unit tests under AddressSanitizer + UBSan |
| [counter-16bit](https://github.com/imtuaz/counter-16bit) | 16-bit counter taken from Verilog RTL to GDSII with OpenLane on SKY130 | Self-checking testbench PASS; DRC 0, LVS clean; timing met at 100 MHz on all corners |

### Tools

- **Languages:** C, Verilog, Python, MATLAB
- **Embedded:** STM32 (HAL, Standard Peripheral Library), UART, I2C, SPI, ESP8266/ESP32
- **Digital IC:** OpenLane (Yosys, OpenROAD, Magic, Netgen), SKY130 PDK, Icarus Verilog, GTKWave/Surfer, KLayout; Synopsys VCS and Design Vision in coursework labs
- **Workflow:** Git, Make, Linux (WSL)

### Contact

- LinkedIn: [ho-anhtuan](https://www.linkedin.com/in/ho-anhtuan/)
- Email: atuan.ho0305@gmail.com
