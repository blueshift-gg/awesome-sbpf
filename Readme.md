# Awesome sBPF

A collection of awesome resources for learning sBPF Assembly (Solana eBPF). PRs welcome!

### Tooling:
- [sbpf](https://github.com/blueshift-gg/sbpf) - a tool to bootstrap, build, debug, deploy, disassemble, and test sBPF assembly programs
- [vscode-sbpf-asm](https://marketplace.visualstudio.com/items?itemName=deanmlittle.vscode-sbpf-asm) - VSCode plugin for sBPF ASM syntax and autocomplete

### Documentation
- [bpf.wtf opcodes](https://bpf.wtf/sol-0x03-isa) - an archive of [@riptl](https://github.com/riptl) old website explaining opcodes.
- [bpf.wtf syscalls](https://bpf.wtf/sol-0x04-syscalls) - an archive of [@riptl](https://github.com/riptl) old website explaining syscall APIs.
- [rbpf opcodes](https://github.com/anza-xyz/sbpf/blob/main/src/ebpf.rs) - the opcodes of the ebpf library used in agave with inline documentation in code comments.
- [firedancer rbpf opcodes](https://github.com/firedancer-io/firedancer/blob/main/src/ballet/sbpf/fd_sbpf_opcodes.h) - the opcodes of sBPF used in firedancer's vm
- [assembly directives](https://ftp.gnu.org/old-gnu/Manuals/gas-2.9.1/html_chapter/as_7.html) - glossary of assembly directives used by lld, the default linker used by LLVM

### Rust Resources
- [sbpf-asm-macros](https://github.com/deanmlittle/sbpf-asm-macros) - some useful macros for inline ASM in rust to save CUs
- [sbpf-inline-asm](https://github.com/deanmlittle/sbpf-inline-asm) - an example of writing inline assembly in a Rust contract

### Smart contracts
- [TOKEN.sbpf](https://github.com/firedancer-io/token.sbpf) - a sample of a hand-rolled token contract
- [solana-program-rosetta](https://github.com/joncinque/solana-program-rosetta/) - a collection of contracts implemented in C, Rust, Zig and sBPF ASM
- [sbpf-asm-noop](https://github.com/deanmlittle/sbpf-asm-noop) - a bytecode optimal noop program with a custom linker file demonstrating extreme binary optimization
- [sbpf-asm-slippage](https://github.com/deanmlittle/sbpf-asm-slippage) - a tiny slippage detection instruction in just 4CUs
- [solaba-fibonacci-asm](https://github.com/deanmlittle/solana-fibonacci-asm) - a fibonacci number solver written in sBPF assembly
- [sbpf-asm-noop](https://github.com/deanmlittle/sbpf-asm-noop) - a heavily optimized sBPF assembly implementation of noop
- [sbpf-asm-slippage](https://github.com/deanmlittle/sbpf-asm-slippage) - a tiny IX for slippage checks written in sBPF ASM
- [sbpf-asm-sha256](https://github.com/deanmlittle/sbpf-asm-sha256) - a simple example of using assembly to hash a string and return it in base64
- [sbpf-asm-memo](https://github.com/deanmlittle/sbpf-asm-memo) - a memo program in sBPF assembly
- [sbpf-asm-afterburner](https://github.com/deanmlittle/sbpf-asm-afterburner) - a program to burn the remaining number of CUs in a transaction
- [sbpf-asm-timeout](https://github.com/deanmlittle/sbpf-asm-timeout) - an sBPF ASM optimized slot-height based cancel instruction
- [sbpf-asm-timeout-account](https://github.com/deanmlittle/sbpf-asm-timeout-account) - account version of sbpf-asm-timeout
- [sbpf-asm-abort](https://github.com/deanmlittle/sbpf-asm-abort) - an sBPF implementation to shut down a program in a recoverable way in a single transaction
- [sbpf-asm-pda](https://github.com/bidhan-a/sbpf-asm-pda) - a program to derive and validate PDAs in sBPF Assembly
- [sbpf-asm-cpi](https://github.com/bidhan-a/sbpf-asm-cpi) - an sBPF assembly program to transfer lamports via CPI
- [sbpf-asm-vault](https://github.com/bidhan-a/sbpf-asm-vault) - a Solana vault program written in sBPF Assembly
