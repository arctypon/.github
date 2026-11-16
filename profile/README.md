# arctypon

**Open-source actor-model kernels & runtimes in `no_std` Rust —
built on [Asterinas OSTD/OSDK](https://github.com/asterinas/asterinas).**

Message passing all the way down: arctypon explores operating systems where
everything is an actor, written in safe Rust on the framekernel architecture.

## The series

| Crate | Purpose | Status |
|---|---|---|
| `arctypon` | Actor kernel built on OSTD | 🚧 early stage |
| `arctypon-core` | Core actor & message abstractions (`no_std`) | 📋 planned |
| `arctypon-runtime` | Scheduler and message dispatch | 📋 planned |
| `arctypon-macros` | Procedural macros | 📋 planned |

> Names are reserved for the series; crates will appear on
> [crates.io](https://crates.io) as they are published.

## Design principles

- `no_std` first; 100% safe Rust outside the framework layer
- Actors and message passing over shared state
- Small, auditable core

## License

All arctypon code is dual licensed under
[MIT](https://opensource.org/licenses/MIT) OR
[Apache-2.0](https://www.apache.org/licenses/LICENSE-2.0), at your option.
Upstream Asterinas OSTD/OSDK components are licensed under MPL-2.0.

## Trademarks

"arctypon"™ and the arctypon logo are trademarks of 靈月夜 (Luna-night).
The code licenses grant no trademark rights. Forks must be renamed and
clearly marked as unofficial.

arctypon is an independent project and is not affiliated with or endorsed
by the Asterinas project.
