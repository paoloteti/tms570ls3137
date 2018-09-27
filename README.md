[![Build Status](https://travis-ci.org/paoloteti/tms570ls3137.svg?branch=master)](https://travis-ci.org/paoloteti/tms570ls3137)

# TMS570LS3137 BSP Example

Example on how to use the TMS570 BSP crate.

## Getting started

* Rust nightly as default toolchain
  * Latest tested: `rustc 1.30.0-nightly (4141a4079 2018-09-25)`
* Add an armebv7r target:
  * Hard-float: `rustup target add armebv7r-none-eabihf`
  * Soft-float: `rustup target add armebv7r-none-eabi`
* GCC v7.3.2 for ARM: `sudo apt-get install gcc-arm-none-eabi`
* JTAG programmer: Lautherbach Trace32 Powerview for ARM or OpenOCD

## Build

Just run `cargo build` or `cargo build --release`

## License

Licensed under either of

- Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or
  http://www.apache.org/licenses/LICENSE-2.0)
- MIT license ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

at your option.

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in the work by you, as defined in the Apache-2.0 license, shall be dual
licensed as above, without any additional terms or conditions.
