# Rust Installation

## Let's install Rust

Refer to the [Rust officials's doc](https://www.rust-lang.org/tools/install) to install rust according to your OS

## Rustup installation

Open your terminal/prompt cmd and paste the follwing code

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

To check if rustup has been installed succesful, run the code to check its installed version

```bash
rustc --version
```

## Upgrade rust

If you have already installed `rustup` in the past, you can run the commnand

```bash
rustup update
```

You'll see something like this

```bash
rustup update
info: syncing channel updates for 'stable-aarch64-apple-darwin'
info: latest update on 2024-11-28, rust version 1.83.0 (90b35a623 2024-11-26)
info: downloading component 'rust-src'
info: downloading component 'cargo'
info: downloading component 'clippy'
info: downloading component 'rust-docs'
info: downloading component 'rust-std'
 25.7 MiB /  25.7 MiB (100 %)  15.6 MiB/s in  1s ETA:  0s
info: downloading component 'rustc'
 53.1 MiB /  53.1 MiB (100 %)  19.1 MiB/s in  1s ETA:  0s
info: downloading component 'rustfmt'
info: removing previous version of component 'rust-src'
info: removing previous version of component 'cargo'
info: removing previous version of component 'clippy'
info: removing previous version of component 'rust-docs'
info: removing previous version of component 'rust-std'
info: removing previous version of component 'rustc'
info: removing previous version of component 'rustfmt'
info: installing component 'rust-src'
info: installing component 'cargo'
info: installing component 'clippy'
info: installing component 'rust-docs'
 16.5 MiB /  16.5 MiB (100 %)   1.8 MiB/s in  6s ETA:  0s
info: installing component 'rust-std'
 25.7 MiB /  25.7 MiB (100 %)  20.6 MiB/s in  1s ETA:  0s
info: installing component 'rustc'
 53.1 MiB /  53.1 MiB (100 %)  21.8 MiB/s in  2s ETA:  0s
info: installing component 'rustfmt'
info: checking for self-update

  stable-aarch64-apple-darwin updated - rustc 1.83.0 (90b35a623 2024-11-26) (from rustc 1.81.0 (eeb90cda1 2024-09-04))

info: cleaning up downloads & tmp directories
```

## Uninstall rust

If you'd like to uninstall rust, on your terminal, you can run the command

```bash
rustup self uninstall
```
