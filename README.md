# Development environments driven by Nix flakes

| Language/framework/tool | Project               |
| :---------------------- | :-------------------- |
| [Node.js][node]         | [`node`](./node/)     |
| [Python]                | [`python`](./python/) |
| [Rust]                  | [`rust`](./rust/)     |

## Revisions

| Input                                                                    | Revision                                                                                                                            |
| :----------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------- |
| [`github:NixOS/nixpkgs`](https://github.com/NixOS/nixpkgs)               | [`8937eaacc0b2bd5a365943fd959adb3cad56ad73`](https://github.com/NixOS/nixpkgs/tree/8937eaacc0b2bd5a365943fd959adb3cad56ad73)        |
| [`github:numtide/flake-utils`](https://github.com/numtide/flake-utils)   | [`bee6a7250dd1b01844a2de7e02e4df7d8a0a206c`](https://github.com/numtide/flake-utils/tree/bee6a7250dd1b01844a2de7e02e4df7d8a0a206c)  |
| [`github:oxalica/rust-overlay`](https://github.com/oxalica/rust-overlay) | [`3e95d6696b51f88b3ebfc7a21aefaeeb70a245bd`](https://github.com/oxalica/rust-overlay/tree/3e95d6696b51f88b3ebfc7a21aefaeeb70a245bd) |

The GitPod environment has [Nix] installed and [flakes] enabled.

[flakes]: https://nixos.wiki/wiki/Flakes
[nix]: https://nixos.org
[node]: https://nodejs.org
[python]: https://python.org
[rust]: https://rust-lang.org