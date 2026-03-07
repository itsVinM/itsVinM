## Projects

<table>
<tr>
<td width="50%" valign="top">

### 🎮 CHIP-8 Emulator
![C++](https://img.shields.io/badge/C%2B%2B17-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Google Test](https://img.shields.io/badge/Google%20Test-coverage-red?style=for-the-badge)
![SDL2](https://img.shields.io/badge/SDL2-renderer-121013?style=for-the-badge)

First validation target of the framework. Established the ports-and-adapters interface all subsequent targets implement. Includes an integrated debugger (breakpoints, register inspection, step/continue), fault injection on CPU registers and stack, and 95%+ branch coverage via Python-controlled test harness.

<img width="250" height="250" alt="Screenshot 2025-10-05 at 11 39 47" src="https://github.com/user-attachments/assets/94ea7b6f-f52b-4097-ac21-542e92f48505" />

[→ itsVinM/CHIP-8_Emulator](https://github.com/itsVinM/CHIP-8_Emulator)

</td>
<td width="50%" valign="top">

### 🕹️ Game Boy — LR35902
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![proptest](https://img.shields.io/badge/proptest-property--based-purple?style=for-the-badge)
![Tests](https://img.shields.io/badge/tests-500%2B-brightgreen?style=for-the-badge)

Cycle-accurate LR35902 emulator in Rust. 500+ tests: property-based CPU invariants, golden-file PPU regression, V-blank jitter analysis. Integrated debugger with memory watch and fault injection. Pokémon Red boots to title screen as the end-to-end acceptance test.

<img width="250" height="250" src="https://github.com/itsVinM/gameboy_emu_poke/blob/main/images/emualtor_first.png">

[→ itsVinM/gameboy_emu_poke](https://github.com/itsVinM/gameboy_emu_poke)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚡ STM32 Self-Health Monitor
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Embedded](https://img.shields.io/badge/no__std-embedded-blue?style=for-the-badge)
![probe-rs](https://img.shields.io/badge/probe--rs-GDB-orange?style=for-the-badge)

🚧 In progress — coming Q3 2026

<!-- Bare-metal Rust firmware on STM32. Health monitor FSM (OK → DEGRADED → CRITICAL → FAULT), IWDG watchdog, CRC32 startup verification, and stack watermarking. Python framework controls the target via UART — fault injection, automated pass/fail reporting, same interface as the emulator targets.
[→ itsVinM/stm32_health](https://github.com/itsVinM/stm32_health)
-->

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

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B17-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
