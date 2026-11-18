# The Cesium Programming Language

[![Website](https://img.shields.io/badge/website-cesiumlang.org-blue)](https://cesiumlang.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> A compiled, statically-typed systems programming language designed for mathematical computing and linear algebra applications.

## Repositories

| Repository | What |
| --- | --- |
| [cesium](https://github.com/cesiumlang/cesium) | The compiler. Today: the bootstrap compilers, `cesium0` in portable C and `cesium1` written in Cesium's S0 subset. Design decisions are recorded as issues there. |
| [cesiumlang.org](https://github.com/cesiumlang/cesiumlang.org) | The website: language reference, compiler documentation and the draft specification. |
| [devkits](https://github.com/cesiumlang/devkits) | Prebuilt toolchain packages the compiler is built with: a pinned Zig, the LLVM and LLD libraries, and QBE. |
| [grammar](https://github.com/cesiumlang/grammar) | TextMate grammar and other resources for syntax highlighters. |
| [vscode-cesium](https://github.com/cesiumlang/vscode-cesium) | The VS Code extension. No code yet; it is to be a client of the language server in the compiler. |
| [cesium-workspace](https://github.com/cesiumlang/cesium-workspace) | The parent repository: it holds the others as submodules, with one VS Code workspace for all of them. Clone this one to work on Cesium. |
| [cspell-cesium](https://github.com/cesiumlang/cspell-cesium) | cSpell dictionary of Cesium terms. |
| [cesium-buildtools](https://github.com/cesiumlang/cesium-buildtools) | Windows scripts that install tools the devkit does not contain. |

## Learning Resources

- **Official website:** [cesiumlang.org](https://cesiumlang.org)
- **Language reference and specification draft:** on the website
- **Editor support:** grammar files in the [grammar repository](https://github.com/cesiumlang/grammar)

---

**Note**: Cesium is under active development. APIs and language features may change as the language evolves. Check the individual repository READMEs for the most up-to-date information.
