# CAP-rs
A Rust library for interacting with systems that implement the [Common Alerting Protocol](http://docs.oasis-open.org/emergency/cap/v1.2/CAP-v1.2-os.html).
This crate intends to implement version 1.2 of the protocol. Support for versions
lower than 1.2 will be determined and designed after the completion of the 1.2 effort.

The full scope of compatibility for this library is:
* [Common Alerting Protocol 1.2](http://docs.oasis-open.org/emergency/cap/v1.2/CAP-v1.2-os.html)
* [IPAWS 1.0](http://docs.oasis-open.org/emergency/cap/v1.2/ipaws-profile/v1.0/cs01/cap-v1.2-ipaws-profile-cs01.html)

# Usage
TBD

# Building and Testing
A local build from source can be completed by running `cargo build --release`.
The test suite can be run via the `cargo test` command. For additional support,
check the cargo documentation via `cargo help test`.
