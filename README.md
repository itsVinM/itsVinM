## 🛠️ Low-Level Shenanigans
Where I break things (on purpose) to see how they work. This section covers emulators, custom debuggers, and various ways to inject chaos into silicon.

<table>
<tr>
<td width="50%" valign="top">

### 👾 CHIP-8 Emulator
![C++](https://img.shields.io/badge/C%2B%2B17-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![SDL2](https://img.shields.io/badge/SDL2-renderer-121013?style=for-the-badge)

The "Hello World" of systems programming, but over-engineered for your protection. This was the guinea pig for my ports-and-adapters architecture. 

* **The Goods:** Integrated debugger (breakpoints/stepping) and a Python test harness that hits **95%+ branch coverage**. 
* **The Fun Part:** Custom fault injection. Because why just run code when you can intentionally corrupt the CPU registers?

<img width="250" height="250" alt="CHIP-8 Screen" src="https://github.com/user-attachments/assets/94ea7b6f-f52b-4097-ac21-542e92f48505" />

[→ Check the source](https://github.com/itsVinM/CHIP-8_Emulator)

</td>
<td width="50%" valign="top">

### 🕹️ Game Boy — LR35902
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)

A cycle-accurate LR35902 emulator written in Rust, because memory safety and 1989 handhelds are a match made in heaven.

* **The Rigor:** 500+ tests including property-based CPU invariants and V-blank jitter analysis. 
* **The Milestone:** Successfully boots *Pokémon Red* to the title screen. If Oak says it's time to go, the emulator says it's time to go.
* **The Twist:** Includes memory watch and fault injection for when you want to see a Game Boy struggle.

<img width="250" height="250" src="https://github.com/itsVinM/gameboy_emu_poke/blob/main/images/emualtor_first.png">

[→ View on GitHub](https://github.com/itsVinM/gameboy_emu_poke)

</td>
</tr>
</table>
