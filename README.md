# Os_project
Adding your own OS features

# OS Project – xv6 Enhancements

This project is based on [xv6](https://pdos.csail.mit.edu/6.1810/), a re-implementation of Unix Version 6 (v6) for RISC-V multiprocessors. It builds upon the original xv6 by introducing new features and modifications for educational and experimental purposes.

## 📁 Project Structure

```
OS_Project-main/
├── kernel/         # Core kernel source code (C and Assembly)
├── .vscode/        # Editor configurations
├── LICENSE         # Licensing info
├── Makefile        # Build configuration
├── README          # Original xv6 documentation
```

## 🔧 Features / Enhancements

- ✅ Custom system calls (e.g., `countsyscall.c`)
- ✅ Kernel-level enhancements and bug fixes
- ✅ File system and process management improvements
- ✅ Compatibility with RISC-V architecture
- ✅ Modular organization and support for VSCode development

## 🚀 Getting Started

### Prerequisites

- RISC-V toolchain (`riscv64-unknown-elf-gcc`)
- `make` utility
- Emulator like QEMU

### Build & Run

```bash
make qemu
```

Other useful commands:

```bash
make        # Builds the kernel
make clean  # Removes build artifacts
```

## 📚 References

- [xv6 GitHub Repository](https://github.com/mit-pdos/xv6-riscv)
- [MIT 6.1810 Operating System Engineering](https://pdos.csail.mit.edu/6.1810/)
- Lions' Commentary on UNIX 6th Edition

## 📄 License

This project is distributed under the MIT License. See `LICENSE` for more information.
