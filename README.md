> [!WARNING]
> This crate has been archived. Development has moved to the [zksync-crypto](https://github.com/matter-labs/zksync-crypto) repository.
> Please use it instead.

# pairing "community edition"

Now published as `pairing_ce` to `crates.io` for users convenience.

Originally developed by ZCash, with extensions from us to make it a little more pleasant. 

This is a Rust crate for using pairing-friendly elliptic curves. Currently, only the [BLS12-381](https://z.cash/blog/new-snark-curve.html) and BN256 curves are implemented.

## [Documentation](https://docs.rs/pairing/)

Bring the `pairing` crate into your project just as you normally would.

## Security Warnings

This library does not make any guarantees about constant-time operations, memory access patterns, or resistance to side-channel attacks.

## License

Licensed under either of

 * Apache License, Version 2.0, ([LICENSE-APACHE](LICENSE-APACHE) or http://www.apache.org/licenses/LICENSE-2.0)
 * MIT license ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

at your option.

### Contribution

Unless you explicitly state otherwise, any contribution intentionally
submitted for inclusion in the work by you, as defined in the Apache-2.0
license, shall be dual licensed as above, without any additional terms or
conditions.
