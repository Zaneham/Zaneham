# G'day, Kia Ora

I'm Zane, a self-taught developer based in New Zealand. I work on compilers, chip design tools, and GPU software, mostly in C99 with zero dependencies. Currently building a CUDA compiler that targets AMD and Tenstorrent hardware, and synthesising processors onto silicon with my own synthesis tool.

Everything is built from primary sources, original manuals, and the occasional declassified document.

If you'd like to see my write ups on some of these projects my website is [zanehambly.com](https://zanehambly.com)

---

## Highlights

**[Takahe](https://github.com/Zaneham/Takahe)** - Open-source digital synthesis tool that takes SystemVerilog and VHDL down to gate-level netlists targeting four open PDKs (SKY130 130nm, IHP SG13G2, GF180MCU, ASAP7 7nm). Supporting thirteen computing paradigms including ternary, quantum, and probabilistic architectures. Place and route through OpenROAD

**[BarraCUDA](https://github.com/Zaneham/BarraCUDA)** - Open-source CUDA compiler with three backends: AMD (RDNA 2/3/4, CDNA3), NVIDIA (PTX), and Tenstorrent Tensix. First CUDA compiled and running on Tenstorrent's non-SIMT RISC-V dataflow architecture. 20K+ lines of C99 with zero LLVM dependency, covering the full pipeline from preprocessor through to ELF emission

**[Moa](https://github.com/Zaneham/Moa)** - Monte Carlo neutron transport code, GPU-accelerated via BarraCUDA with validated k_eff against MCNP reference values. Runs on RTX 4060 Ti and MI300X

---

## Chip Design

Synthesised with Takahe to open PDKs, place and route via OpenROAD

- **[voyager-fds](https://github.com/ZaneHam/voyager-fds)** - JPL Voyager flight computer on silicon, 58 gates, fabrication-ready
- **[ruru](https://github.com/ZaneHam/ruru)** - Probabilistic processor with distributions as a native data type, 2,237 gates
- **[qsim](https://github.com/ZaneHam/qsim)** - 8-qubit quantum gate simulator on silicon, 238 gates at 200 MHz
- **[setun-70](https://github.com/ZaneHam/setun-70)** - Soviet ternary computer on silicon
- **[minuteman-d17b](https://github.com/ZaneHam/minuteman-d17b)** - Minuteman ICBM guidance computer on silicon

## Compilers

- **[Karearea](https://github.com/Zaneham/Karearea)** - Fortran 77 compiler passing 259/259 tests and compiling all 735 SLATEC files, with PE-COFF and ELF output in C99 with zero dependencies
- **[jovial-compiler](https://github.com/Zaneham/jovial-compiler)** - MIL-STD-1589C JOVIAL compiler built from the original military spec
- **[Wasabi](https://github.com/Zaneham/Wasabi)** - WebAssembly to x86-64 AOT compiler with zero dependencies
- **[conway](https://github.com/Zaneham/conway)** - RISC-V to x86-64 binary translator written in assembly
- **[plankalkul-compiler](https://github.com/Zaneham/plankalkul-compiler)** - Compiler for Zuse's 1945 Plankalkül with 2D notation and all 7 loop variants
- **[hal-s-compiler](https://github.com/Zaneham/hal-s-compiler)** - HAL/S compiler, on pause pending HALMAT work
- **[chill-compiler](https://github.com/Zaneham/chill-compiler)** - CHILL to C transpiler
- **[coral-66-compiler](https://github.com/Zaneham/Coral-66-Compiler-)** - Coral 66 compiler, work in progress

## Upstream Contributions

- **[OCaml](https://github.com/ocaml/ocaml)** - Occasional contributor to the native code compiler backend: [#14575](https://github.com/ocaml/ocaml/pull/14575), [#14547](https://github.com/ocaml/ocaml/pull/14547), [#14524](https://github.com/ocaml/ocaml/pull/14524), [#14515](https://github.com/ocaml/ocaml/pull/14515)
- **[z390](https://github.com/z390development/z390)** - Core contributor to the IBM mainframe assembler/emulator, including COBOL macros, VSAM enhancements, and NIST test suite work
- **[tinygrad](https://github.com/tinygrad/tinygrad)** - RDNA2 emulator support for the AMD GPU backend
- **[qemu-zane](https://github.com/Zaneham/qemu-zane)** - QEMU fork adding QTSan for binary-only data race detection using shadow memory and vector clocks

## Scientific Computing

- **[SLATEC](https://github.com/Zaneham/SLATEC)** - Modernising the SLATEC numerical library
- **[dcuhre](https://github.com/Zaneham/dcuhre)** - Multi-dimensional adaptive integration
- **[odepackzane](https://github.com/Zaneham/odepackzane)** - ODE solvers

## Language Servers

IDE support for languages that predate syntax highlighting:

[HAL/S](https://github.com/Zaneham/hals-lsp) · [JOVIAL](https://github.com/Zaneham/jovial-lsp) · [CMS-2](https://github.com/Zaneham/CMS-2-lsp) · [CORAL 66](https://github.com/Zaneham/coral66-lsp) · [CHILL](https://github.com/Zaneham/chill-lsp) · [COBOL F / PL/I F](https://github.com/Zaneham/IBM-system360-LSP) · [MUMPS](https://github.com/Zaneham/mumps-lsp) · [RACF](https://github.com/Zaneham/racf-lsp)

## Emulators

[Voyager FDS](https://github.com/Zaneham/voyager-fds-emulator) · [Minuteman ICBM](https://github.com/Zaneham/minuteman-computer-emulator) ([assembler](https://github.com/Zaneham/minuteman-assembler)) · [Setun-70](https://github.com/Zaneham/setun70-emulator) · [Viking Mars Lander](https://github.com/Zaneham/viking-marsrover-emulator)

## Mainframe

- **[zblas](https://github.com/Zaneham/zblas)** - z/OS native BLAS written in HLASM with z13+ vector SIMD and dual calling conventions
- **[hlasm-strong-type](https://github.com/Zaneham/hlasm-strong-type)** - VS Code LSP providing type checking for registers, labels, and macros

[HLASM for Notepad++](https://github.com/Zaneham/hlasm-npp) · [RACF LSP](https://github.com/Zaneham/racf-lsp) · [zkvs](https://github.com/Zaneham/zkvs) · [hlasm-http](https://github.com/Zaneham/hlasm-http) · [COBOL todo app](https://github.com/Zaneham/My-todo-app)

## Historical Languages & Cryptography

- **[plankalkul-ide](https://github.com/Zaneham/plankalkul-ide)** - VS Code extension with a 2D grid editor, [on the Marketplace](https://marketplace.visualstudio.com/items?itemName=zaneham.plankalkul)
- **[KW-26 ROMULUS](https://github.com/Zaneham/KW-26-ROMULUS)** - Cold War cryptographic equipment reconstructed from declassified documents
- **[dead-reckoning](https://github.com/Zaneham/dead-reckoning)** - Digital dead man's switch with Shamir secret sharing and duress codes

[Plankalkül interpreter](https://github.com/Zaneham/plankalkuel) · [Plankalkül package manager](https://github.com/Zaneham/ppm) · [Zuse's 1942 chess program](https://github.com/Zaneham/zuse-chess-1942) · [FLOW-MATIC](https://github.com/Zaneham/flow-matic)

## Developer Tools

- **[Olint](https://github.com/Zaneham/Olint)** - OCaml linter with auto-fix, think clippy for OCaml
- **[Halmat](https://github.com/Zaneham/Halmat)** - Resurrecting the HAL/S compiler intermediate language

---

```
Production:          C99, OCaml, Fortran, Python, HLASM, various assemblers
Compiler Internals:  OCaml backend (Lambda → CMM → Mach → asm), QEMU plugin API
GPU:                 AMD GFX9-12 ISA, NVIDIA PTX, Tenstorrent Tensix, HSA runtime
Chip Design:         SystemVerilog, VHDL, SKY130, IHP SG13G2, GF180MCU, ASAP7, OpenROAD
Legacy/Preservation: COBOL, JOVIAL, CMS-2, CORAL 66, CHILL, MUMPS, PL/I, HAL/S
Emulated Hardware:   IBM System/360, Voyager FDS, Minuteman, Setun-70, Viking Lander
Methodology:         Primary sources, original manuals, declassified documentation
```

---

Based in New Zealand, GMT+12/13

**zanehambly@gmail.com**

This is a hobby, not a job search. My day job is in finance. I build this stuff because I find it interesting, and I'm happy to collaborate with anyone who feels the same way. That said, if the right opportunity came along I wouldn't turn it down. I do take contract work from time to time, and I have an optional internship component as part of my degree at AUT if anything lines up, but none of that is why any of this exists. 

If by any chance you work in the charity space and need help please feel free to reach out. I actively volunteer my expertise to a few organisations. 
