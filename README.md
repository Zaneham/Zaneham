# G'day, Kia Ora, and... Hello

I'm Zane. I work on compilers, emulators, and tooling. Sometimes for modern systems, sometimes for machines older than most democracies. Currently contributing to the OCaml native compiler and building a thread sanitiser for QEMU.

Some of this is preservation. Some of it is practical. All of it is built in public because waiting until things are "ready" is how projects die in private folders.

The projects below are in various states of completion and will be worked on from time to time. You're more than welcome to reach out if you use something I've made and are encountering a problem. Some projects are just 'as is' because no one will be updating the FLOW-MATIC standards anytime soon.

---

## What I Do (Allegedly)

### Compiler Contributions

Upstream contributions to production compilers and runtimes:

- **[OCaml](https://github.com/ocaml/ocaml)** - Contributing to the native code compiler backend:
  - [#14524](https://github.com/ocaml/ocaml/pull/14524) - Native `Iatomic_fetch_add` using s390x LAAG instruction
  - [#14515](https://github.com/ocaml/ocaml/pull/14515) - Intel CET/IBT support (`endbr64` landing pads)
  - [#14514](https://github.com/ocaml/ocaml/pull/14514) - s390x shared library initialisation fix
- **[z390](https://github.com/z390development/z390)** - IBM mainframe assembler/emulator (core contributor). COBOL macro implementations (STRING, UNSTRING, SEARCH, SORT, MERGE, REPLACE), VSAM enhancements, and NIST test suite work
- **[qemu-zane](https://github.com/Zaneham/qemu-zane)** - QEMU fork adding QTSan: binary-only data race detection using shadow memory and vector clocks. Because QEMU didn't have TSan and someone had to fix that

### Language Server Protocols for Languages Your Nan Used

Because someone has to maintain IDE support for programming languages older than most democracies:

- **[hals-lsp](https://github.com/Zaneham/hals-lsp)** - Space Shuttle programming, minus the shuttle
- **[jovial-lsp](https://github.com/Zaneham/jovial-lsp)** - For when the US Air Force needs syntax highlighting
- **[cms2-lsp](https://github.com/Zaneham/cms2-lsp)** - US Navy's finest, now with autocomplete
- **[coral66-lsp](https://github.com/Zaneham/coral66-lsp)** - British military computing, as God intended
- **[chill-lsp](https://github.com/Zaneham/chill-lsp)** - ITU telecom standard. We are also pretty Chill
- **[IBM-system-360-lsp](https://github.com/Zaneham/IBM-system360-LSP)** - COBOL F, PL/I F, and HLASM for the discerning mainframe enthusiast
- **[mumps-lsp](https://github.com/Zaneham/mumps-lsp)** - Yes, MUMPS. Yes, it's real. Yes, your hospital probably runs on it
- **[racf-lsp](https://github.com/Zaneham/racf-lsp)** - IBM mainframe security. In development

### Compilers and Translators

- **[conway](https://github.com/Zaneham/conway)** - RISC-V to x86-64 binary translator. Written in assembly
- **[plankalkul-compiler](https://github.com/Zaneham/plankalkul-compiler)** - OCaml compiler for Zuse's 1945 Plankalkül. 2D notation, all 7 loop variants, chess programs from the original manuscripts
- **[hal-s-compiler](https://github.com/Zaneham/hal-s-compiler)** - HAL/S compiler. The Space Shuttle programming language
- **[chill-compiler](https://github.com/Zaneham/chill-compiler)** - CHILL to C transpiler. Because someone asked "but can it run on modern hardware"
- **[jovial-compiler](https://github.com/Zaneham/jovial-compiler)** - MIL-STD-1589C compliant JOVIAL compiler. Built from the original military specification
- **[coral-66-compiler](https://github.com/Zaneham/Coral-66-Compiler-)** - Coral 66 compiler. Work in progress

### Emulators for Questionable Hardware

- **[voyager-fds-emulator](https://github.com/Zaneham/voyager-fds-emulator)** - Voyager Flight Data Subsystem. The computer that's leaving the solar system
- **[minuteman-computer-emulator](https://github.com/Zaneham/minuteman-computer-emulator)** - ICBM guidance computer. I'm probably on a list now
- **[minuteman-assembler](https://github.com/Zaneham/minuteman-assembler)** - Assembler for the above. Because you need to program the thing somehow
- **[setun70-emulator](https://github.com/Zaneham/setun70-emulator)** - Soviet ternary computer. Because binary is for capitalists
- **[viking-marsrover-emulator](https://github.com/Zaneham/viking-marsrover-emulator)** - 1970s Mars lander. 40KB of RAM. Absolute unit

### Fortran Modernisation

Keeping scientific computing alive, one 50-year-old numerical library at a time:

- **[SLATEC](https://github.com/Zaneham/SLATEC)** - Modernising the SLATEC library for modern Fortran
- **[SLATEC.jl](https://github.com/Zaneham/SLATEC.jl)** - Julia port of SLATEC. Work in progress
- **[dcuhre](https://github.com/Zaneham/dcuhre)** - Multi-dimensional adaptive integration. Riveting stuff
- **[odepackzane](https://github.com/Zaneham/odepackzane)** - ODE solvers, now with fewer punch cards

### Historical Languages (Not Dead, Just Resting)

- **[plankalkul-ide](https://github.com/Zaneham/plankalkul-ide)** - VS Code extension for Plankalkül with 2D grid editor. **[On the Marketplace](https://marketplace.visualstudio.com/items?itemName=zaneham.plankalkul)**
- **[plankalkuel](https://github.com/Zaneham/plankalkuel)** - Python interpreter for Plankalkül. The prototype that started this
- **[ppm](https://github.com/Zaneham/ppm)** - Plankalkül Package Manager. Because even 1945 deserves nice things
- **[zuse-chess-1942](https://github.com/Zaneham/zuse-chess-1942)** - Chess like it's 1941
- **[flow-matic](https://github.com/Zaneham/flow-matic)** - Grace Hopper's business language. COBOL's mum, basically

### Cryptography

- **[KW-26-ROMULUS](https://github.com/Zaneham/KW-26-ROMULUS)** - KW-26 ROMULUS cryptographic equipment
- **[dead-reckoning](https://github.com/Zaneham/dead-reckoning)** - Digital dead man's switch. Shamir secret sharing, duress codes, encrypted cargo

### Other Bits

- **[hlasm-http](https://github.com/Zaneham/hlasm-http)** - HTTP client written in HLASM. Because mainframes deserve the internet too
- **[My-todo-app](https://github.com/Zaneham/My-todo-app)** - Todo app in COBOL. Enterprise-grade task management
- **[wu](https://github.com/Zaneham/wu)** - Media forensics toolkit. For legal and institutional teams
- **[nistcobol85](https://github.com/z390development/nistcobol85)** - NIST COBOL 85 test suite. 11,000 test cases of pure joy

---

## Tech Stack

```
Production:          Python, C, OCaml, Fortran, Java, Julia, various Assemblers
Compiler Internals:  OCaml backend (Lambda → CMM → Mach → asm), QEMU plugin API
Legacy/Preservation: COBOL, JOVIAL, CMS-2, CORAL 66, CHILL, MUMPS, PL/I, HAL/S, HLASM
Emulated Hardware:   IBM System/360, Voyager FDS, Minuteman, Setun-70, Viking Lander
Methodology:         Primary sources. Original manuals. Declassified documentation.
                     If there's a spec, I read it. If there's a manuscript, I implement from it.
```

---

## Contact

Based in New Zealand. GMT+12/13. Already in your future.

**zanehambly@gmail.com**

Available for contract work, collaboration, or just to chat. Can help with legacy systems modernisation, compiler development, safety-critical systems, and the occasional impossible project. Anyone got an internship lying around? 
