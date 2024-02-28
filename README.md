# RISyx

## Project Overview:

RISyx is a lightweight and customizable RISC-V kernel designed for efficiency and flexibility. It aims to provide low-level control over hardware resources while maintaining portability and ease of maintenance.

## License:

This project is licensed under the GNU General Public License v3.0. See the [LICENSE](LICENSE) file for details.

## Project Goals:

TBC - But there is one question to start with:  If RISC-V is meant to change a
paradigm with it's open architecture, can't we create a kernel to fully
complimemt this? Why default to waiting on a port of an existing one? Innovation
creates more innovation!

## Development TODO List:

Main development and contribution to RISyx should follow these stages:

0. **Clone the Repository**: 
- git clone https://github.com/yourusername/RISyx.git

1. **Set Up Development Environment**:
- Determine a RISC-V toolchain for assembling and compiling code targeting RISC-V architecture.
- Determine a development environment with appropriate tools for building, debugging, and testing your kernel code.
- Determine an emulator or a RISC-V development board for testing your kernel.

2. **Write Code**:
- Write assembly code to initialize the processor, sets up the environment, and jump to the main C entry point.
- Implement basic functions (memory initialization, interrupt handling, and context switching).
- Main kernel logic to be implemented in C, including scheduler, memory management, file system support (if needed), device drivers, and system calls.

3. **Integration**:
- Integrate the assembly and C code to create a unified kernel image.
- Set up linker scripts to define memory layout and sections for the kernel image.

4. **Testing**:
- Thorough testing to ensure boot, interrupt handling, memory management, and performs basic system operations as expected.
- Use emulators, simulators, or hardware (if available) to test kernel on different RISC-V platforms.

5. **Iterate and Refine**:
- Iterate design to add features and improve performance and stability.
- Code refinements based on testing feedback and performance analysis.

6. **Contribute**:
- If you'd like to contribute to RISyx, fork the repository, make your changes, and submit a pull request. Ensure your code follows the project's coding conventions and passes all tests.

