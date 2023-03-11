# bevy_mod_gltf_patched

[![crates.io](https://img.shields.io/crates/v/bevy_mod_gltf_patched.svg)](https://crates.io/crates/bevy_mod_gltf_patched)
[![docs](https://docs.rs/bevy_mod_gltf_patched/badge.svg)](https://docs.rs/bevy_mod_gltf_patched)

This crate is a fork of [Bevy's](https://bevyengine.org/) first-party
`bevy_gltf` crate with a patch introducing [support for custom vertex
attributes](https://github.com/bevyengine/bevy/pull/5370). This crate
will be deprecated once such functionality is available in mainline Bevy.

## Dependency

```toml
[dependencies]
bevy_mod_gltf_patched = "0.2"
```

## Example

A mesh with barycentric coordinates used to draw variable-width borders around
the triangles.

```shell
cargo run --example custom_gltf_2d
```

## Versions

| This Version | Bevy version |
|--------------|--------------|
| 0.1.x        | 0.9.x        |
| 0.2.x        | 0.10.x       |

## Licence

This crate is licensed under the Apache License, Version 2.0 (see
LICENCE-APACHE or <http://www.apache.org/licenses/LICENSE-2.0>) or the MIT
licence (see LICENCE-MIT or <http://opensource.org/licenses/MIT>), at your
option.

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall
be dual licensed as above, without any additional terms or conditions.
