**Systems Validation Engineer** — hardware-software co-test, embedded Rust, fault injection.

Space-grade QRNG validation at Quside (Barcelona). Previously: GaN/Si parametric characterization at Nexperia UK, ISO 16750 automotive validation at Applus+ IDIADA, railway power converter V&V at Premium PSU.

---

### Active projects

**[Digital Analyzer](https://github.com/itsVinM/digital_analyzer)** `Rust · SCPI`
Oscilloscope automation with real-time telemetry, binary waveform parsing, fault injection, and automated pass/fail reporting. Used to externally validate STM32 firmware timing against spec limits.

**[Game Boy Emulator — LR35902](https://github.com/itsVinM/gameboy_emulator)** `Rust · proptest`
Cycle-accurate LR35902 emulator. 500+ tests: property-based CPU invariants, golden-file PPU regression, V-blank jitter analysis. Pokemon Red boots to title screen as the end-to-end acceptance test.

**[CHIP-8 Emulator](https://github.com/itsVinM/CHIP-8_Emulator)** `C++17 · Google Test · SDL2`
First validation target of the framework. Established the ports-and-adapters interface that all subsequent targets implement. Fault injection, branch coverage, stack overflow to defined safe state.

---

### Work context

These projects are not independent — they share a single test framework with a common `ValidationTarget` interface. CHIP-8 was where the interface was designed. Game Boy stress-tested it. STM32 brings it to real silicon. The same fault taxonomy, structured reporting format, and test isolation pattern appears across all of them.

That's the same discipline applied at Quside: modular Python validation framework for space-grade QRNGs, SCPI-based instrument automation, NIST SP 800-90B entropy validation, hardware-software co-debugging.

---

### Stack

`Python` `Rust` `C++17` `Linux` `SCPI` `GDB` `probe-rs` `Google Test` `proptest`
`ISO 26262` `ISO 16750` `NIST SP 800-90B` `JEDEC` `CANoe` `INCA`

