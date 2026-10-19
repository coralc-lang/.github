# Coral

**Coral** is a systems programming language that keeps the C mental model while adding the features large-scale systems work needs — with no hidden machinery and costs you can see in the source.

Coral began with a single question: can a language keep everything that makes C great, add the modern features that make big systems productive, provide genuine safety, and still let programmers think the way C already taught them to think? Every feature has to pass three tests:

- **Preserve the C mental model** — learning Coral never means unlearning how memory and the machine work.
- **Hide no machinery** — nothing runs behind your back.
- **Make cost visible in the code** — every copy, allocation, dispatch, and check is written down.

The result is a language for the software closest to the hardware: operating systems, device drivers, kernels, embedded firmware, game engines, databases, browsers, compilers, network stacks, and high-performance libraries.

- Native machine code — no interpreter, no virtual machine, no garbage collector.
- Direct hardware access; data laid out byte by byte.
- Manual memory management with smart pointers, explicit error values, and a choice of allocators.
- Predictable performance: you get what you write.
- Generics, `comptime`, traits and `extend`, tuples, and a modern type system in a C-shaped syntax.

## Links

- **Textbook & documentation:** https://coralc-lang.github.io/coral-docs/
- **Documentation source:** https://github.com/coralc-lang/coral-docs
