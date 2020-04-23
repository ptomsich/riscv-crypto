
# RISC-V Cryptography Extension

*RISC-V cryptography extensions standardisation work.*

---

- [About](#About)
- [Specification](#Specification)
- [Toolchain](#Toolchain)
- [Benchmarks](#Benchmarks)
- [Verilog RTL](#Verilog-RTL-Prototypes)

## About

- **Note:** See the
   [dev/next-release](https://github.com/scarv/riscv-crypto/tree/dev/next-release)
   branch for the most up to date version.

- This repository is used to develop standardisation proposals for
  scalar cryptographic instruction set extensions for the RISC-V
  architecture.

- **Note:** These instructions are a work in progress. Their specifications
  will to change before being accepted as part of the RISC-V standard.  While
  there are *experimental* encodings assigned to the proposed instructions,
  they *should not* be depended upon.  They only exist to enable a toolchain
  and simulator flow.  They *will* change.

- The Scalar Cryptography extension proposals overlap significantly
  with the [Bitmanip extension](https://github.com/riscv/riscv-bitmanip).
  Hence, we are experimenting with *sharing* opcodes between extensions.

- Some of the proposals in this repository are based on work done as part of
  the [XCrypto](https://github.com/scarv/xcrypto) project by the University
  of Bristol Cryptography Group on scalar cryptography extensions
  to RISC-V.

- There is a rough [Todo List](todo.md).

## Specification

To see the latest draft release of the proposals, look at the
[Releases](https://github.com/scarv/riscv-crypto/releases) tab of
the [Github Repository](https://github.com/scarv/riscv-crypto).


## Toolchain

See [tools/README.md](tools/README.md) for instructions on how to
build the experimental toolchain.

## Benchmarks

See [`benchmarks/README.md`](benchmarks/README.md) for how to
get started with the benchmarking flow and how to contribute new
benchmarks.

## Verilog RTL Prototypes

See [`rtl/README.md`](rtl/README.md) for information on experimental
RTL implementations of the proposed instructions.

