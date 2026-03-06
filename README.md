# Vincentiu Mocanu

**Systems Validation Engineer** — hardware-software co-test · embedded Rust · fault injection

Space-grade QRNG at **Quside** · GaN/Si at **Nexperia UK** · ISO 16750 automotive at **Applus+ IDIADA** · railway V&V at **Premium PSU**

---

## Projects

<table>
<tr>
<td width="50%" valign="top">

### ⚡ STM32 + Digital Analyzer
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Embedded](https://img.shields.io/badge/no__std-embedded-blue?style=for-the-badge)
![SCPI](https://img.shields.io/badge/SCPI-instrument--control-yellow?style=for-the-badge)
![probe-rs](https://img.shields.io/badge/probe--rs-GDB-orange?style=for-the-badge)

STM32F401RE firmware (IWDG watchdog, CRC32 startup, stack watermarking, health FSM) validated externally by a Rust CLI digital analyzer — GPIO capture, UART decode, fault injection, automated pass/fail reports. Hardware and test harness written in the same language, closing the loop end-to-end.

[→ itsVinM/STM32_HealthCheck](https://github.com/itsVinM/STM32_HealthCheck) · [→ itsVinM/digital_analyzer](https://github.com/itsVinM/digital_analyzer)

</td>
<td width="50%" valign="top">

### 🕹️ Game Boy — LR35902
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![proptest](https://img.shields.io/badge/proptest-property--based-purple?style=for-the-badge)
![Tests](https://img.shields.io/badge/tests-500%2B-brightgreen?style=for-the-badge)

Cycle-accurate LR35902 emulator. 500+ tests: property-based CPU invariants, golden-file PPU regression, V-blank jitter analysis. Pokemon Red boots to title screen as the end-to-end acceptance test.

[→ itsVinM/gameboy_emulator](https://github.com/itsVinM/gameboy_emulator)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎮 CHIP-8 Emulator
![C++](https://img.shields.io/badge/C%2B%2B17-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Google Test](https://img.shields.io/badge/Google%20Test-coverage-red?style=for-the-badge)
![SDL2](https://img.shields.io/badge/SDL2-renderer-121013?style=for-the-badge)

First validation target of the framework. Established the ports-and-adapters interface all subsequent targets implement. Fault injection, 95%+ branch coverage, stack overflow to defined safe state.

[→ itsVinM/CHIP-8_Emulator](https://github.com/itsVinM/CHIP-8_Emulator)

</td>
<td width="50%" valign="top">

### 🚗 Powertrain Analysis Tool
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)

Comparative web app for powertrain architecture trade-off studies. Models system architectures and visualises key performance metrics for fast engineering decisions.

[→ Live tool](https://itsvinm-powertrain-case-selection-powertrain-sim-1k95tr.streamlit.app/) · [→ itsVinM/Powertrain_Case_Selection](https://github.com/itsVinM/Powertrain_Case_Selection)

</td>
</tr>
</table>

---

## Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B17-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)

**Validation & Embedded**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![GDB](https://img.shields.io/badge/GDB-debugger-red?style=for-the-badge)
![SCPI](https://img.shields.io/badge/SCPI-instrument--control-yellow?style=for-the-badge)
![probe-rs](https://img.shields.io/badge/probe--rs-embedded-orange?style=for-the-badge)
![CANoe](https://img.shields.io/badge/CANoe-Vector-darkblue?style=for-the-badge)
![INCA](https://img.shields.io/badge/INCA-ETAS-blue?style=for-the-badge)

**Standards**

![ISO 26262](https://img.shields.io/badge/ISO%2026262-functional--safety-cc0000?style=for-the-badge)
![ISO 16750](https://img.shields.io/badge/ISO%2016750-automotive--env-cc0000?style=for-the-badge)
![ISO 50155](https://img.shields.io/badge/ISO%2050155-railway-cc0000?style=for-the-badge)
![NIST SP 800-90B](https://img.shields.io/badge/NIST%20SP%20800--90B-entropy-cc0000?style=for-the-badge)
![JEDEC](https://img.shields.io/badge/JEDEC-semiconductor-cc0000?style=for-the-badge)

---

📍 Barcelona — open to relocation &nbsp;|&nbsp; 🔗 [LinkedIn](https://linkedin.com/in/vincentiu-mocanu-b06274182) &nbsp;|&nbsp; 📧 vincentiu.mocanu00@gmail.com