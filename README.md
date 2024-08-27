# RISC-V bare metal "BIOS" example
This program prints "hello" from Virtual Uart using a Risc-v processor on VirtIO target machine in Qemu EMulator

To build the "fake BIOS", simply run `make hello`.

Run with QEMU: `qemu-system-riscv64 -machine virt -bios hello`
