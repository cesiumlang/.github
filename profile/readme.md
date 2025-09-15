# The Cesium Programming Language

[![Website](https://img.shields.io/badge/website-cesiumlang.org-blue)](https://cesiumlang.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> A compiled, statically-typed systems programming language designed for mathematical computing and linear algebra applications.

## Overview

Cesium is a performance-oriented programming language that prioritizes explicit memory management, mathematical expressiveness, and C ABI compatibility. Drawing inspiration from languages like C, Zig, MATLAB, Python, Fortran, Rust, Go, and Odin, Cesium provides a modern approach to systems programming with first-class support for mathematical operations.

The language name is a reference to the atomic element cesium (American Chemical Society spelling). Since one of the primary objectives is runtime performance, it seemed fitting to share a name with the element used in atomic clocks - where a second is officially defined by the Cs-133 atom's hyperfine transition frequency of exactly 9,192,631,770 Hz.

## Key Features

- **🧮 Math-first Design**: Built-in mathematical operators and types optimized for numerical computing
- **⚡ High Performance**: Compile-time dispatch, static optimization, and predictable performance characteristics
- **🛡️ Memory Safety**: Ownership tracking and compile-time borrow checking with explicit memory management
- **🔗 C Interoperability**: Seamless integration with existing C libraries and systems
- **📝 Clear Syntax**: ASCII-only syntax for universal accessibility and readability
- **🎯 Static Typing**: Strong type system with minimal implicit conversions

### Design Goals

- Explicit control over memory management and performance characteristics
- Mathematical expressiveness through context-aware operators
- Memory safety without garbage collection overhead
- Strong typing with compile-time verification
- Universal accessibility through ASCII-only syntax
- Production-ready systems programming capabilities

## Quick Start

Here's a simple "Hello, World!" program in Cesium:

```cesium
// hello.cs
void = main() {
  printf("Hello, Cesium!\n");
}
```

## Repository Structure

The Cesium language ecosystem is organized across several repositories:

| Repository | Description | Language |
|------------|-------------|----------|
| [**cesium**](https://github.com/cesiumlang/cesium) | Main compiler and language implementation | CMake/C++ |
| [**grammar**](https://github.com/cesiumlang/grammar) | Grammar files for syntax highlighting and IDE support | Grammar definitions |
| [**cesium-buildtools**](https://github.com/cesiumlang/cesium-buildtools) | Build toolchain and development tools | Batchfile |
| [**cesiumlang.org**](https://github.com/cesiumlang/cesiumlang.org) | Official website and documentation | TypeScript |
| [**cspell-cesium**](https://github.com/cesiumlang/cspell-cesium) | Spell checking configuration for Cesium code | JSON |

## Getting Started

### Prerequisites

- **Windows**: Install the [Windows SDK](https://developer.microsoft.com/en-us/windows/downloads/windows-sdk/)
- **Compiler**: Clang (installable via our [buildtools](https://github.com/cesiumlang/cesium-buildtools))

### Building from Source

1. Clone the main repository:

   ```bash
   git clone https://github.com/cesiumlang/cesium.git
   cd cesium
   ```

2. Follow the build instructions in the [cesium repository](https://github.com/cesiumlang/cesium)

## Learning Resources

- 📖 **Official Website**: [cesiumlang.org](https://cesiumlang.org)
- 📚 **Language Documentation**: Available on the website
- 🔧 **Build Tools**: [cesium-buildtools](https://github.com/cesiumlang/cesium-buildtools)
- 🎨 **Editor Support**: Grammar files in [grammar repository](https://github.com/cesiumlang/grammar)

## Contributing

We welcome contributions to the Cesium programming language! Here's how you can get involved:

1. **Report Issues**: Found a bug or have a feature request? Open an issue in the relevant repository
2. **Contribute Code**: Check out the open issues and submit pull requests
3. **Improve Documentation**: Help make Cesium more accessible by improving documentation
4. **Share Feedback**: Join discussions and share your experience using Cesium

For major contributions, please open an issue first to discuss your ideas with the maintainers.

## Community

- 💬 **Discussions**: Use GitHub Discussions in the relevant repositories
- 🐛 **Bug Reports**: Open issues in the specific repository where the bug was found
- 🚀 **Feature Requests**: Submit feature requests as issues with detailed descriptions

## License

The Cesium programming language is released under the [MIT License](https://opensource.org/licenses/MIT).

---

**Note**: Cesium is under active development. APIs and language features may change as the language evolves. Check the individual repository READMEs for the most up-to-date information.
