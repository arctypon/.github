# Contributing to arctypon

## Licensing of contributions
Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be
dual licensed as MIT OR Apache-2.0, without any additional terms or conditions.

## Pull requests
- Run `cargo fmt` and `cargo clippy` before submitting.
- New source files carry `// SPDX-License-Identifier: MIT OR Apache-2.0`.
- Files copied or modified from Asterinas OSTD/OSDK remain under MPL-2.0.
- Kernel crates: build and test with `cargo osdk build` / `cargo osdk test`.
