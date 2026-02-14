# G'day, Kia Ora

I'm Zane. I work on compilers, emulators, and tooling for systems that range from current to older than most countries. Currently contributing to the OCaml native compiler, resurrecting HALMAT and building a thread sanitiser for QEMU.

Built in public. Some of this is preservation, some is practical.

---

## Compiler Contributions

Upstream contributions to production compilers and runtimes:

- **[OCaml](https://github.com/ocaml/ocaml)** - Native code compiler backend:
  - [#14524](https://github.com/ocaml/ocaml/pull/14524) - Native `Iatomic_fetch_add` using s390x LAAG instruction
  - [#14515](https://github.com/ocaml/ocaml/pull/14515) - Intel CET/IBT support (`endbr64` landing pads)
- **[z390](https://github.com/z390development/z390)** - IBM mainframe assembler/emulator. COBOL macro implementations, VSAM enhancements, NIST test suite work
- **[qemu-zane](https://github.com/Zaneham/qemu-zane)** - QEMU fork adding QTSan: binary-only data race detection using shadow memory and vector clocks

## Language Server Protocols

IDE support for legacy languages:

- **[hals-lsp](https://github.com/Zaneham/hals-lsp)** - HAL/S (Space Shuttle)
- **[jovial-lsp](https://github.com/Zaneham/jovial-lsp)** - JOVIAL (US Air Force)
- **[cms2-lsp](https://github.com/Zaneham/cms2-lsp)** - CMS-2 (US Navy)
- **[coral66-lsp](https://github.com/Zaneham/coral66-lsp)** - CORAL 66 (British MoD)
- **[chill-lsp](https://github.com/Zaneham/chill-lsp)** - CHILL (ITU telecom)
- **[IBM-system-360-lsp](https://github.com/Zaneham/IBM-system360-LSP)** - COBOL F, PL/I F
- **[mumps-lsp](https://github.com/Zaneham/mumps-lsp)** - MUMPS. Your hospital probably runs on it
- **[racf-lsp](https://github.com/Zaneham/racf-lsp)** - IBM RACF security. In development

## Compilers and Translators

- **[conway](https://github.com/Zaneham/conway)** - RISC-V to x86-64 binary translator, written in assembly
- **[plankalkul-compiler](https://github.com/Zaneham/plankalkul-compiler)** - OCaml compiler for Zuse's 1945 Plankalkül. 2D notation, all 7 loop variants
- **[hal-s-compiler](https://github.com/Zaneham/hal-s-compiler)** - HAL/S compiler
- **[chill-compiler](https://github.com/Zaneham/chill-compiler)** - CHILL to C transpiler
- **[jovial-compiler](https://github.com/Zaneham/jovial-compiler)** - MIL-STD-1589C JOVIAL compiler, built from the original military spec
- **[coral-66-compiler](https://github.com/Zaneham/Coral-66-Compiler-)** - Coral 66 compiler. Work in progress

## Emulators

- **[voyager-fds-emulator](https://github.com/Zaneham/voyager-fds-emulator)** - Voyager Flight Data Subsystem
- **[minuteman-computer-emulator](https://github.com/Zaneham/minuteman-computer-emulator)** - Minuteman ICBM guidance computer
- **[minuteman-assembler](https://github.com/Zaneham/minuteman-assembler)** - Assembler for the above
- **[setun70-emulator](https://github.com/Zaneham/setun70-emulator)** - Soviet ternary computer
- **[viking-marsrover-emulator](https://github.com/Zaneham/viking-marsrover-emulator)** - Viking Mars lander. 40KB of RAM

## Fortran Modernisation

- **[SLATEC](https://github.com/Zaneham/SLATEC)** - Modernising the SLATEC numerical library
- **[SLATEC.jl](https://github.com/Zaneham/SLATEC.jl)** - Julia port. Work in progress
- **[dcuhre](https://github.com/Zaneham/dcuhre)** - Multi-dimensional adaptive integration
- **[odepackzane](https://github.com/Zaneham/odepackzane)** - ODE solvers

## Historical Languages

- **[plankalkul-ide](https://github.com/Zaneham/plankalkul-ide)** - VS Code extension for Plankalkül with 2D grid editor. [On the Marketplace](https://marketplace.visualstudio.com/items?itemName=zaneham.plankalkul)
- **[plankalkuel](https://github.com/Zaneham/plankalkuel)** - Python interpreter for Plankalkül
- **[ppm](https://github.com/Zaneham/ppm)** - Plankalkül Package Manager
- **[zuse-chess-1942](https://github.com/Zaneham/zuse-chess-1942)** - Zuse's 1942 chess program, reconstructed
- **[flow-matic](https://github.com/Zaneham/flow-matic)** - Grace Hopper's FLOW-MATIC

## Cryptography

- **[KW-26-ROMULUS](https://github.com/Zaneham/KW-26-ROMULUS)** - KW-26 ROMULUS cryptographic equipment
- **[dead-reckoning](https://github.com/Zaneham/dead-reckoning)** - Digital dead man's switch. Shamir secret sharing, duress codes, encrypted cargo

## Other

- **[zkvs](https://github.com/Zaneham/zkvs)** - Database engine in HLASM. Sequential I/O working, B-tree indexing next
- **[hlasm-http](https://github.com/Zaneham/hlasm-http)** - HTTP client in HLASM
- **[My-todo-app](https://github.com/Zaneham/My-todo-app)** - Todo app in COBOL
- **[wu](https://github.com/Zaneham/wu)** - Media forensics toolkit
- **[nistcobol85](https://github.com/z390development/nistcobol85)** - NIST COBOL 85 test suite

---

```
Production:          Python, C, OCaml, Fortran, Java, Julia, various Assemblers
Compiler Internals:  OCaml backend (Lambda → CMM → Mach → asm), QEMU plugin API
Legacy/Preservation: COBOL, JOVIAL, CMS-2, CORAL 66, CHILL, MUMPS, PL/I, HAL/S, HLASM
Emulated Hardware:   IBM System/360, Voyager FDS, Minuteman, Setun-70, Viking Lander
Methodology:         Primary sources. Original manuals. Declassified documentation.
```

---

Based in New Zealand. GMT+12/13.

**zanehambly@gmail.com**

Available for contract work, collaboration, or conversation about legacy systems, compiler development, and safety-critical software. Also looking for an internship as part of my degree with AUT. Right to work in New Zealand, the UK, Australia, and the EU.
