+++
title = "Setup Repository"
+++

## Installing Rust

Before we get started with writing code, we need to install Rust and setup
the repository. Run the following in your terminal, then follow the onscreen
instructions:

```bash
$ curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

After installing Rust, run following to configure your current shell:

```bash
$ source $HOME/.cargo/env
```

## Create project

Next, head over to any folder of your choice, then create a new project with `cargo`:

```bash
$ cargo new klang
     Created binary (application) `klang` package
$ cd klang
```

Lets also add some dependencies we'll need:

```bash
$ cargo install cargo-edit
$ cargo add nom fehler anyhow
    Updating 'https://github.com/rust-lang/crates.io-index' index
      Adding nom v7.1.1 to dependencies.
             Features:
             + alloc
             + memchr/std
             + minimal-lexical/std
             + std
             - docsrs
      Adding fehler v1.0.0 to dependencies.
      Adding anyhow v1.0.57 to dependencies.
             Features:
             + std
             - backtrace
```
