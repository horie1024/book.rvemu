# Writing a RISC-V Emulator from Scratch in 10 Steps

## Introduction

This is the book for writing a RISC-V emulator from scratch in Rust. It shows us how to implement an emulator step by step in 10 steps. You can run [xv6](https://github.com/mit-pdos/xv6-riscv), a simple Unix-like OS, in your emulator in the final day.

You'll learn the basic computer architecture from making an emulator in Rust:

* Basic RISC-V architecture
* How to write code in Rust language
* Privilege levels
* Exceptions
* Interrupts
* Peripheral devices

The source code is available at [d0iasm/rvemu-for-book](https://github.com/d0iasm/rvemu-for-book).

| Step | Content |
| :--- | :--- |
| Step 1 | [Setup and implement two instructions](setup-and-implement-one-instruction.md) |
| Step 2 | [RV64I ISAs](rv64i-isas.md) |
| Step 3 | Supervisor ISAs |
| Step 4 | A part of CSRs |
| Step 5 | Exceptions |
| Step 6 | UART \(a universal asynchronous receiver-transmitter\) |
| Step 7 | PLIC \(a platform-level interrupt controller\) |
| Step 8 | Interrupts |
| Step 9 | CLINT \(a core-local interruptor\) |
| Step 10 | Virtio |

Congratulations🎉 Now you can run xv6 in your emulator!

Author is [@d0iasm](https://twitter.com/d0iasm) and please feel free to ask and request anything to me via [Twitter](https://twitter.com/d0iasm) or [GitHub issues](https://github.com/d0iasm/rvemu-simple/issues)!

