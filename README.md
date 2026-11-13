# moss-core-nif

Precompiled NIFs of `moss_core`, the native runtime of the [Moss Elixir SDK](https://hex.pm/packages/moss).
When [`moss_core`](https://hex.pm/packages/moss_core) compiles, RustlerPrecompiled downloads the archive for
its version and target from this repository's releases and checks it against the checksums the Hex package ships.

Each `elixir-nif-vX.Y.Z` release holds one archive per target: `x86_64-unknown-linux-gnu`,
`aarch64-unknown-linux-gnu`, `aarch64-apple-darwin` and `x86_64-pc-windows-msvc`.

## License

The NIF binaries are licensed under the [PolyForm Shield License 1.0.0](https://polyformproject.org/licenses/shield/1.0.0),
in [`LICENSE.txt`](LICENSE.txt). From `elixir-nif-v0.25.0`, each archive carries that `LICENSE.txt`, and
`LICENSE-THIRD-PARTY.txt` with the licenses of the third-party code the NIF links.

Required Notice: Copyright InferEdge Inc. (https://inferedge.dev)
