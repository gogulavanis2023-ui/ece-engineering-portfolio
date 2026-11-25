# Engineering Portfolio: Gogulavani S

**B.Tech, Electronics and Communication Engineering, VIT Vellore (2023–2027)**
FPGA / RTL design · Embedded systems · Automotive electronics · Signal processing

I take digital designs from specification through RTL, verification and timing closure to working hardware, and I build embedded systems around real sensors and buses. Interested in RTL/FPGA design, design verification and embedded firmware roles in Chennai or Bengaluru.

---

## Featured projects

| Project | Domain | Technologies | Status | Repository |
|---|---|---|---|---|
| Runtime-Reconfigurable Parallel FIR Filter | FPGA / DSP | Verilog, Vivado, Artix-7, DSP48, Python, SAIF power | ✅ Complete: implemented, WNS +2.64 ns @ 100 MHz, bit-exact vs. golden model | [fpga-reconfigurable-fir-filter](https://github.com/gogulavanis2023-ui/fpga-reconfigurable-fir-filter) |
| Parallel GPS C/A Code Acquisition Engine (IIT Madras research internship) | FPGA / GNSS | Verilog, Vivado, Artix-7, LFSR, MATLAB | ✅ Complete: 32 runtime-selectable correlators, WNS +5.85 ns | [fpga-gps-ca-code-acquisition](https://github.com/gogulavanis2023-ui/fpga-gps-ca-code-acquisition) |
| CAN-Bus ECU Voltage Fingerprinting IDS | Automotive / Embedded ML | CAN, MCP2515, STM32, Arduino, Python, scikit-learn, LaTeX | 🔄 In progress: CAN bench working; detection pipeline validated in simulation | [can-ecu-voltage-fingerprinting-ids](https://github.com/gogulavanis2023-ui/can-ecu-voltage-fingerprinting-ids) |
| Asynchronous FIFO with Gray-Code CDC | VLSI / FPGA | Verilog, Quartus, SDC, Cyclone IV | ✅ Complete: self-checking scoreboard testbench, on DE2-115 | [async-fifo-cdc-verilog](https://github.com/gogulavanis2023-ui/async-fifo-cdc-verilog) |

## Other projects

| Project | Domain | Technologies | Status | Repository |
|---|---|---|---|---|
| Verilog Digital Design Labs | Digital design | Verilog, ModelSim, Quartus | ✅ Complete | [verilog-digital-design-labs](https://github.com/gogulavanis2023-ui/verilog-digital-design-labs) |
| Line-Follower Robots (Arduino → ESP32 PID over Bluetooth) | Robotics / Embedded | Arduino, ESP32, PID, Bluetooth | ✅ Complete | [arduino-esp32-line-follower](https://github.com/gogulavanis2023-ui/arduino-esp32-line-follower) |
| RF Amplifier Stability and Max-Gain Analysis | RF | Python, NumPy, S-parameters | ✅ Complete | [rf-amplifier-stability-analysis](https://github.com/gogulavanis2023-ui/rf-amplifier-stability-analysis) |

## Documented projects (reports only; source code not available)
| Project | Domain | Summary |
|---|---|---|
| Li-Fi Controlled Robot | Optical comms / Robotics | Robot commanded over a visible-light link |
| Adaptive Edge-AI Fault Prediction | Embedded C | Fault prediction on embedded hardware |
| Solar-Powered Visible Light Communication | Optical / analog | LED transmitter, photodiode receiver, analog filtering |

---

## Projects by domain

**FPGA and digital design:** FIR filter · GPS acquisition engine · Async FIFO · Verilog labs
**VLSI / RTL verification:** Async FIFO (CDC, scoreboard TB) · FIR filter (bit-exact golden-model verification, timing closure)
**Embedded systems:** CAN IDS (STM32 + MCP2515 over SPI) · ESP32 PID line follower
**Automotive electronics:** CAN IDS (physical-layer sender authentication, CUSUM attack detection)
**Signal processing / communications:** FIR filter design (Kaiser window, fixed point) · GPS C/A codes and correlation · RF amplifier analysis

## Skills shown in these repositories
- **HDL and FPGA:** Verilog, parameterised and generate-based RTL, pipelining, fixed-point arithmetic, LFSRs, CDC (Gray code and synchronisers)
- **Tools:** Xilinx Vivado (synthesis, implementation, timing, SAIF power, XSim), Intel Quartus Prime (SDC), ModelSim
- **Verification:** self-checking testbenches, scoreboards, golden reference models in Python
- **Embedded:** Arduino, ESP32, STM32 (STM32duino), SPI, CAN (MCP2515/TJA1050), UART, PWM, Bluetooth
- **Software:** Python (NumPy, SciPy, scikit-learn, Matplotlib), MATLAB, LaTeX

## Experience
- **Research Intern, IIT Madras** (May–Jul 2026): runtime-configurable parallel GPS acquisition engine on Artix-7
- **Embedded Systems Intern, C Systems Pvt Ltd, Chennai** (May–Jul 2025): PIC-based industrial temperature monitoring firmware (company code not published)
