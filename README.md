# Rust / Wasm / Wgpu Triangle

This project demonstrates how to setup a [rust](https://www.rust-lang.org/) project
that uses [wgpu](https://wgpu.rs/) to render a triangle, supporting
both [wasm](https://webassembly.org/) and native.

```
# native
cargo run -r 

# web
trunk serve --open
```

## Prerequisites (web)

* [trunk](https://trunkrs.dev/)