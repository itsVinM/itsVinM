## 🛠️ Systems & Architecture
A collection of projects focused on low-level system design, hardware emulation, and reliability engineering.

---

### 👾 CHIP-8 Go Runtime
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Ebitengine](https://img.shields.io/badge/Ebitengine-8BD0BA?style=for-the-badge&logo=ebitengine&logoColor=white)
![WASM](https://img.shields.io/badge/WebAssembly-624DE8?style=for-the-badge&logo=webassembly&logoColor=white)

A hardened execution environment built with a **"Quality-First"** mindset. This project shifts the focus from simple interpretation to a resilient, production-ready virtual machine.

* **Engineering Rigor:** Built-in fault injection and deterministic halt states to ensure system stability.
* **WASM Deployment:** Fully automated CI/CD pipeline targeting high-performance browser execution.
* **Test-Driven:** Dynamic regression suite validating instruction parity across the entire ROM collection.

| Runtime with Debugger | WASM Runtime |
| :---: | :---: |
|<img width="250" alt="CHIP-8 Go Runtime" src="https://github.com/itsVinM/chip8-go-runtime/blob/main/statics/tank.png"/>| <img width="250" alt="CHIP-8 WASM" src="https://github.com/itsVinM/chip8-go-runtime/blob/main/statics/chip8_wasm.png"/>|

**[🚀 Live Demo](https://itsVinM.github.io/chip8-go-runtime/) | [→ Source Code](https://github.com/itsVinM/chip8-go-runtime)**

---

### 🕹️ Game Boy — LR35902
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![minifb](https://img.shields.io/badge/minifb-brown?style=for-the-badge&logo=rust&logoColor=white)
![WASM](https://img.shields.io/badge/WebAssembly-624DE8?style=for-the-badge&logo=webassembly&logoColor=white)

A cycle-accurate LR35902 emulator designed for high-fidelity execution and state-based verification. This project demonstrates the migration of legacy C-based hardware logic into a modern, memory-safe Rust architecture.

* **Verification:** Validated by 500+ tests, including property-based CPU invariants and V-blank jitter analysis.
* **System Reliability:** Integrated memory-watch triggers and a custom fault-injection framework for stress-testing.
* **State Serialization:** Implements robust **Save/Load State** (Snapshotting) for persistent execution tracking.
* **Binary Compatibility:** Designed with a decoupled **Cartridge Interface**. To ensure legal compliance, the runtime does not bundle proprietary assets but provides a unified interface for loading user-provided ROM binaries.

| Runtime with Debugger | WASM Runtime |
| :---: | :---: |
| <img width="300" src="https://github.com/itsvinm/gameboy_emu_poke/blob/main/images/debugger.png"> | <img width="300" src="https://github.com/itsvinm/gameboy_emu_poke/blob/main/images/initgameplay.png"> |

**[🚀 Live Demo](https://itsvinm.github.io/gameboy_emu_poke/) | [→ Source Code](https://github.com/itsVinM/gameboy_emu_poke)**
