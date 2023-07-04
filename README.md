![GitHub top language](https://img.shields.io/github/languages/top/philskat/code-stats)
![GitHub](https://img.shields.io/github/license/philskat/code-stats)

# Code Stats

This repo contains a small program that can show a few stats of your code base.
This can be used to give an overview of your own or another code base. What languages are used and
how big the project is.

## Planned features

- Print lines of code
- Print percentage of languages used in the project
- See lines of code per directory/file
- Analyse git data (commits, branches)

## Requirements

To build the project you need to have rust installed.

The easiest way to install Rust ist to use [rustup](https://www.rust-lang.org/learn/get-started)

## Commands

Build the project:

```bash
$ cargo build [--release]
```

Run the tests of the project:

```bash
$ cargo test
```

Run the project:

```bash
$ cargo run
```

## License

This project runs under the [MIT](LICENSE) license.
