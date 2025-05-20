# Awesome sBPF

A collection of awesome resources for learning sBPF Assembly (Solana eBPF). PRs welcome!

### Tooling:
- [sbpf](https://github.com/deanmlittle/sbpf) - a tool to quickly bootstrap, build, deploy and test sbpf assembly programs
- [ezbpf](https://github.com/deanmlittle/ezbpf) - a simple sBPF disassembler library with a CLI and WASM bindings
- [vscode-sbpf-asm](https://marketplace.visualstudio.com/items?itemName=deanmlittle.vscode-sbpf-asm) - VSCode plugin for sBPF ASM syntax and autocomplete

### Documentation
- [bpf.wtf opcodes](https://wayback-api.archive.org/web/20231004134038/https://bpf.wtf/sol-0x03-isa/) - waybackmachine archive of [@riptl](https://github.com/riptl) old website explaining opcodes.
- [bpf.wtf syscalls](https://web.archive.org/web/20231004144333/https://bpf.wtf/sol-0x04-syscalls/) - waybackmachine archive of [@riptl](https://github.com/riptl) old website explaining syscall APIs.
- [rbpf opcodes](https://github.com/solana-labs/rbpf/blob/main/src/ebpf.rs) - the opcodes of the ebpf library used in agave with inline documentation in code comments.
- [firedancer rbpf opcodes](https://github.com/firedancer-io/firedancer/blob/main/src/ballet/sbpf/fd_sbpf_opcodes.h) - the opcodes of sbpf used in firedancer's vm
- [assembly directives](https://ftp.gnu.org/old-gnu/Manuals/gas-2.9.1/html_chapter/as_7.html) - glossary of assembly directives used by lld, the default linker used by LLVM
- [Learn Solana BPF Assembly](https://github.com/7etsuo/Learn-Solana-BPF-Assembly) - a guide for learning SBPF assembly from the ground up

### Rust Resources
- [sbpf-asm-macros](https://github.com/deanmlittle/sbpf-asm-macros) - some useful macros for inline ASM in rust to save CUs
- [sbpf-inline-asm](https://github.com/deanmlittle/sbpf-inline-asm) - an example of writing inline assembly in a Rust contract

### Smart contracts
- [TOKEN.sbpf](https://github.com/firedancer-io/token.sbpf) - a sample of a hand-rolled token contract
- [solana-program-rosetta](https://github.com/joncinque/solana-program-rosetta/) - a collection of contracts implemented in C, Rust, Zig and sBPF ASM
- [sbpf-asm-noop](https://github.com/deanmlittle/sbpf-asm-noop) - a bytecode optimal noop program with a custom linker file demonstrating extreme binary optimization
- [sbpf-asm-slippage](https://github.com/deanmlittle/sbpf-asm-slippage) - a tiny slippage detection instruction in just 4CUs
- [solaba-fibonacci-asm](https://github.com/deanmlittle/solana-fibonacci-asm) - a fibonacci number solver written in sBPF assembly
