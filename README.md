# rod-plugin-unload

unload -- The fresh-copy unhook at breadth: compare any loaded library's mapped .text against a fresh copy and restore it -- the KnownDlls section object the preferred source, the System32 disk file the fallback the row names, the named exports alone or the whole .text -- evasion.unload's execution half packed as the artifact an implant loads th...

A Rod capability module (entry kind: plugin) in the
[Rod](https://github.com/rodframework/Rod) ecosystem. The manifest
(`rod-module.toml`) is the contract; the package installs from the
[rod-registry](https://github.com/rodframework/rod-registry) index:

    rod mod install unload

## Building the artifact

The execution half compiles from the Rust module crates in the Rod
platform tree; `build.sh` drops it at the path the manifest's
`[[plugin.artifacts]]` row names, then `rod mod publish` packs it.
Point `ROD_RUST_TREE` at a Rod checkout's `src/implant/rust` (or an
unpacked `rod-src.tar.gz`):

    ROD_RUST_TREE=/path/to/src/implant/rust ./build.sh

## License

Apache-2.0, as declared in the manifest.
