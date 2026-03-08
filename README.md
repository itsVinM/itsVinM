## 🛠️ Systems & Architecture
A collection of projects focused on low-level system design, emulation, and reliability testing.

<table>
<tr>
<td width="50%" valign="top">

### 👾 CHIP-8 Emulator
![C++](https://img.shields.io/badge/C%2B%2B17-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![SDL2](https://img.shields.io/badge/SDL2-renderer-121013?style=for-the-badge)

My primary validation target for a ports-and-adapters architecture. This project serves as a proof-of-concept for building modular, testable hardware interfaces.

* **Capabilities:** Integrated debugger with real-time register inspection and breakpoint support.
* **Resilience:** Implements a Python-controlled test harness achieving **95%+ branch coverage** and active fault injection on CPU registers.

<img width="250" height="250" alt="CHIP-8 Screen" src="https://github.com/user-attachments/assets/94ea7b6f-f52b-4097-ac21-542e92f48505" />

[→ Source Code](https://github.com/itsVinM/CHIP-8_Emulator)

</td>
<td width="50%" valign="top">

### 🕹️ Game Boy — LR35902
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)

A cycle-accurate LR35902 emulator designed for high-fidelity execution and state-based testing.

* **Verification:** Validated by 500+ tests, including property-based CPU invariants and V-blank jitter analysis.
* **Features:** Integrated memory watch and fault injection framework.
* **Milestone:** Successfully passes end-to-end acceptance tests by booting *Pokémon Red* to the title screen.

<img width="250" height="250" src="https://github.com/itsVinM/gameboy_emu_poke/blob/main/images/emualtor_first.png">

[→ Source Code](https://github.com/itsVinM/gameboy_emu_poke)

</td>
</tr>
</table>
