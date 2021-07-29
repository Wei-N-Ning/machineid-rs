<a href="https://crates.io/crates/machineid-rs"><img src="https://img.shields.io/crates/v/machineid-rs?style=for-the-badge&logo=rust&color=orange" /></a>

## MachineID/HWID for Rust

Get the encrypted HWID/MachineID of a pc running Windows or Linux.

### How to use

First add this to your Cargo.toml file

```toml
[dependencies]
machineid-rs = "1.0.2"
```

Getting the encrypted id is as simple as doing this

```rust
let id_result = machineid_rs::encrypted_id("Your Key").unwrap();
```