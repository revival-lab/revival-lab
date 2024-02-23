---
permalink: /portfolio/
title: Contributions to Open Source Projects
toc: true
toc_sticky: true
---
Selected list of contributions to open source projects.
Where available, links to short video presentations by or with us are provided.

## Science 

### Molecular Simulation

[Faunus](https://githib.com/mlund/faunus) is a scientific software written in modern C++/Python for simulating
molecular systems at multiple length and time scales.
Over two decades we have kept up with the C++ standard and is now at C++17.
_Contribution: creator and development lead_.
{% include video id="mFOooBQE3mg" provider="youtube" %}

### Plotting

[Xmgr](https://github.com/mlund/xmgr-resurrection) is an ancient but still popular GUI tool
for plotting scientific data. It was utterly abandoned until we resurrected the code base.
_Contribution: CMake build system; bug fixes; and support for 64-bit systems._

## Compiler backend

[LLVM-MOS](https://githib.com/llvm-mos) supports the MOS Technology 65xx series of microprocessors and enables C, C++, Rust compilers on a series of 8-bit computers.
_Contribution: memory layout for the MEGA65 and Commander X16 target and implementation of assembler opcodes_.
{% include video id="iPX4ydAPaKo" provider="youtube" %}

## Embedded

### Hardware Abstraction Layers (HAL)

[HAL for MOS Technology graphics and sound chips](https://githib.com/mlund/mos-hardware) using memory-mapped I/O.
<i class="fab fa-rust"></i> Rust.
_Contribution: creator and development lead_
{% include video id="wifYmhIRAEs?start=2532" provider="youtube" %}

### Rust on Espressif ESP Micro-controllers

We have made contributions to the [`esp-idf-hal`](https://crates.io/crates/esp-idf-hal)
crate for running Rust on Espressif's ESP family of micro-controllers.
_Contribution: refactoring of RGB color handling_.

### Graphics Display Driver

We maintain a [library for display drivers](https://crates.io/crates/retro-display)
for graphics on extremely restricted systems using the `embedded-graphics` crate.
_Contribution: creator and development lead_.
<a href="https://crates.io/crates/retro-display">
  <img src="https://github.com/mlund/retro-display/raw/HEAD/assets/c64demo.png" width="500">
</a>

### Hardware Remote Control via HTTP and Serial Communications

[Ultimate64](https://githib.com/mlund/ultimate64) is a CLI for communicating with Ultimate 64/II+ hardware via HTTP requests.
[Matrix65](https://githib.com/mlund/matrix) is a modern text user-interface (TUI) for serial communication with the MEGA65 computer.
<i class="fab fa-rust"></i> Rust.
_Contribution: creator and development lead_.
{% include video id="dUvXLtUUC-Y" provider="youtube" %}

