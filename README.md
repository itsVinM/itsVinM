## System-level projects
Below the main system level projects, which include debuggers and fault injection.

<table>
<tr>
<td width="50%" valign="top">

### 🎮 CHIP-8 Emulator
![C++](https://img.shields.io/badge/C%2B%2B17-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![SDL2](https://img.shields.io/badge/SDL2-renderer-121013?style=for-the-badge)
<!--![Google Test](https://img.shields.io/badge/Google%20Test-coverage-red?style=for-the-badge)-->


First validation target of the framework. Established the ports-and-adapters interface all subsequent targets implement. Includes an integrated debugger (breakpoints, register inspection, step/continue), fault injection on CPU registers and stack, and 95%+ branch coverage via Python-controlled test harness.

<img width="250" height="250" alt="Screenshot 2025-10-05 at 11 39 47" src="https://github.com/user-attachments/assets/94ea7b6f-f52b-4097-ac21-542e92f48505" />

[→ itsVinM/CHIP-8_Emulator](https://github.com/itsVinM/CHIP-8_Emulator)

</td>
<td width="50%" valign="top">

### 🕹️ Game Boy — LR35902
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)


Cycle-accurate LR35902 emulator in Rust. 500+ tests: property-based CPU invariants, golden-file PPU regression, V-blank jitter analysis. Integrated debugger with memory watch and fault injection. Pokémon Red boots to title screen as the end-to-end acceptance test.

<img width="250" height="250" src="https://github.com/itsVinM/gameboy_emu_poke/blob/main/images/emualtor_first.png">

[→ itsVinM/Gameboy_emulator](https://github.com/itsVinM/gameboy_emu_poke)

</td>

</table>


