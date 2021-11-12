# Universal Scene Description (Rust)

IMPORTANT DISCLAIMER: this crate is very experimental and in development. While
it intends to be a pure-Rust alternative to [bindings][usd-rs] to [Pixar's USD][USD],
currently it is entirely unfit to be used for that purpose.

- USD is a high-performance extensible software platform for collaboratively
  constructing animated 3D scenes, designed to meet the needs of large-scale
  film and visual effects production.

- USD provides robust interchange between digital content creation tools with
  its expanding set of schemas, covering domains like geometry, shading,
  lighting, and physics.

- USD’s unique composition features have powerful benefits. For example,
  composition provides rich and varied ways to combine individual assets into
  larger assemblies, and enables workflows that let many users collaborate
  simultaneously without conflict.

For more information, we strongly recommend checking out [Pixar's documentation][USD].

usdr, by necessity, follows behind [Pixar's USD][USD]. Upstream is where
developments to the USD schemas and usda, usdc, and usdz formats are done.
Additionally, usdr does not aim to provide tools for manipulating USD, such
as Hydra; usdr is just concerned with interpreting the file format itself.

## License

Licensed under either of

 * Apache License, Version 2.0
   ([LICENSE/APACHE](LICENSE/APACHE) or http://www.apache.org/licenses/LICENSE-2.0)
 * MIT license
   ([LICENSE/MIT](LICENSE/MIT) or http://opensource.org/licenses/MIT)

at your option.

Some portions of this program may be partially derived from https://github.com/PixarAnimationStudios/USD,
which is licensed under [modified Apache 2.0](https://github.com/PixarAnimationStudios/USD/blob/release/LICENSE.txt);
specifically, clause 6 is modified to read

>    6. Trademarks. This License does not grant permission to use the trade
      names, trademarks, service marks, or product names of the Licensor
      and its affiliates, except as required to comply with Section 4(c) of
      the License and to reproduce the content of the NOTICE file.

Additionally, this license does not free you from needing to comply with this
package's own dendencies. The authors have attempted to keep the dependency
tree properly compatibly licensed (and a failure to do so is considered a bug),
but mistakes happen, and THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF
ANY KIND, EXPRESS OR IMPLIED, et cetera.

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be
dual licensed as above, without any additional terms or conditions.

<!-- Links! -->
  [USD]: https://graphics.pixar.com/usd/release/index.html
  [usd-rs]: https://lib.rs/crates/usd
