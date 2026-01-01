# Liquid Selva

Liquid Selva is a compiled, embeddable, non Turing complete programming language designed for verifiable rules and contract-based programming. It allows developers to embed expressive logic into their software, with types carrying compile-time constraints, and compiles down to LLVM IR, producing highly optimized machine code.

---

## Features

- **Embeddable**: Integrate seamlessly into any host application via the provided library.
- **LLVM Backend**: Generates LLVM IR and compiles to native machine code for high performance.
- **Contract-based Types**: Types can carry constraints, e.g., `Int[>=0]`, `Float[0.0 <= x <= 100.0]`.
- **Compile-time Verification**: Contracts are verified at compile time and absent from runtime errors.
- **No Heap Allocations**: Everything happens on the stack. therefore ideal for embedded systems.
- **No undefined behaviour**: The syntax enforces explicitness and verbosity, preventing hidden or unsafe behavior.

---
