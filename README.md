# semoxide-poc

Throwaway proof-of-concept code for [semoxide](https://github.com/semoxide/semoxide). Not product code. **Every semoxide PoC lives here**, never in the main repo. Measured facts are folded into the main repo's docs.

Moved from `semoxide/semoxide` `poc/` at commit `cfb2460` (2026-10-07); earlier history is in that repo.

| PoC | Status | What it proved |
|---|---|---|
| [git2-ops](git2-ops/README.md) | reference | every semantic-release git op on git2, locally and against real GitHub (Linux + Windows) |
| [git2-russh](git2-russh/README.md) | reference | SSH for git2 via pure-Rust russh (default) or the system `ssh` (opt-in); no libssh2 |
| [plugin-grpc](plugin-grpc/README.md) | reference | the chosen plugin design: gRPC over a named pipe / Unix socket, host services, process-tree kill, conformance |
| [plugin-protocol](plugin-protocol/README.md) | superseded | the earlier stdio/JSON-RPC plugin design and a WASM check |
| [sort-order](sort-order/README.md) | superseded (decided) | `icu_collator` matches JS `localeCompare` exactly |
| [ssh-cost](ssh-cost/README.md) | superseded (decided) | real cost of libssh2 vs russh on the product baseline |

## License

Licensed under either of [Apache License, Version 2.0](LICENSE-APACHE) or [MIT license](LICENSE-MIT), at your option.
