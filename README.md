## 🛠️ Systems & Architecture
A collection of projects focused on low-level system design, emulation, and reliability testing.


### 👾 CHIP-8 Go Runtime
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![WASM](https://img.shields.io/badge/WebAssembly-624DE8?style=for-the-badge&logo=webassembly&logoColor=white)
![Ebitengine](https://img.shields.io/badge/Ebitengine-Powered-orange?style=for-the-badge)

A hardened execution environment built with a "Quality-First" mindset. This project shifts the focus from simple interpretation to a resilient, production-ready virtual machine.

* **Engineering Rigor:** Built-in fault injection and graceful halt states to prevent memory corruption.
* **WASM Deployment:** Fully automated CI/CD pipeline targeting high-performance browser execution.
* **Test-Driven:** Dynamic regression suite validating instruction parity across the entire ROM collection.

<img width="250" height="250" alt="CHIP-8 Go Runtime tank game" src="https://github.com/itsVinM/chip8-go-runtime/blob/main/statics/tank.png"/>

[🚀 Live Demo](https://itsVinM.github.io/chip8-go-runtime/) | [→ Source Code](https://github.com/itsVinM/chip8-go-runtime)

---

### 🕹️ Game Boy — LR35902
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)

A cycle-accurate LR35902 emulator designed for high-fidelity execution and state-based testing.

* **Verification:** Validated by 500+ tests, including property-based CPU invariants and V-blank jitter analysis.
* **Features:** Integrated memory watch and fault injection framework.
* **Milestone:** Successfully passes end-to-end acceptance tests by booting *Pokémon Red* to the title screen.

<img width="250" height="250" src="https://github.com/itsVinM/gameboy_emu_poke/blob/main/images/emualtor_first.png">

[→ Source Code](https://github.com/itsVinM/gameboy_emu_poke)

