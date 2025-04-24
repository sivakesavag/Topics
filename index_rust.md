## Comprehensive List of Rust Topics

**I. Foundations**

1.  **Language Philosophy:** memory safety without GC, fearless concurrency.
2.  **Toolchain:** rustup, cargo, crates, `rustc`, editions (2015, 2018, 2021, 2024).
3.  **Syntax Basics:** variables (`let`, `mut`), shadowing, comments.
4.  **Primitive Types:** integers, floats, bool, char, tuples, arrays.
5.  **Ownership, Borrowing, Lifetimes.**
6.  **Pattern Matching & Control Flow:** `match`, `if let`, loops (`loop`, `while`, `for`).

**II. Data Structures & Smart Pointers**

7.  **Standard Collections:** Vec, String, HashMap, HashSet, VecDeque, BTreeMap.
8.  **Slices & Str vs String.
9.  **Smart Pointers:** Box, Rc, Arc, RefCell, Cell, Mutex, RwLock.
10. **Interior Mutability, Pin, UnsafeCell.

**III. Functions, Closures, Traits**

11. **Functions, generics, trait bounds, lifetimes.
12. **Closures, Fn/FnMut/FnOnce.
13. **Trait System:** default methods, supertraits, associated types.
14. **Derive macros, operator overloading.

**IV. Modules & Crate Ecosystem**

15. **Modules, privacy (`pub`), path imports (`use`).**
16. **Workspaces, feature flags, Cargo.toml.
17. **Common crates:** serde, tokio, async-std, anyhow, thiserror, clap, reqwest, rayon.

**V. Error Handling**

18. **`Result`, `Option`, `?` operator.
19. **Custom error types, `thiserror`, `anyhow`.
20. **Panic vs Result, unwinding, `catch_unwind`.

**VI. Concurrency & Async**

21. **Threads & Channels (`std::sync::mpsc`).**
22. **`Send`, `Sync` traits.
23. **Async/await, `Future`, executors (tokio, async-std).
24. **Pinning, async traits upcoming.

**VII. Unsafe Rust**

25. **Raw pointers, deref, `unsafe` blocks.
26. **FFI (C interop), `repr` attributes.
27. **`unsafe` guidelines & writing safe abstractions.

**VIII. Macros**

28. **Declarative macros (`macro_rules!`).**
29. **Procedural macros: derive, attribute, function-like.
30. **Build scripts (`build.rs`).**

**IX. Testing & Tooling**

31. **Unit & Integration tests (`#[cfg(test)]`).**
32. **Benchmarks, criterion.
33. **Clippy, rustfmt, miri, cargo-audit.
34. **Documentation tests (`rustdoc`).

**X. Web & Systems**

35. **Web Frameworks:** Actix-web, Rocket, Axum.
36. **WASM (`wasm-pack`, wasm-bindgen).**
37. **Embedded Rust (no_std, HALs).
38. **Operating Systems with Rust, drivers, TockOS.

**XI. Resources:** "The Rust Programming Language" (TRPL), Rustonomicon, rustlings, official book.
