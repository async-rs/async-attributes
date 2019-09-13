# async-macros
[![crates.io version][1]][2] [![build status][3]][4]
[![downloads][5]][6] [![docs.rs docs][7]][8]

Procedural macros for async-std.

- [Documentation][8]
- [Crates.io][2]
- [Releases][releases]

## Installation
```sh
$ cargo add async-macros
```

## Safety
This crate uses `unsafe` for pin projections.

## Contributing
Want to join us? Check out our ["Contributing" guide][contributing] and take a
look at some of these issues:

- [Issues labeled "good first issue"][good-first-issue]
- [Issues labeled "help wanted"][help-wanted]

## References
- https://github.com/rust-lang-nursery/futures-rs - the `join` + `try_join`
  macros are direct ports of the old `macro_rules` impls from `futures-rs`.

## License
[MIT](./LICENSE-MIT) OR [Apache-2.0](./LICENSE-APACHE)

[1]: https://img.shields.io/crates/v/async-macros.svg?style=flat-square
[2]: https://crates.io/crates/async-macros
[3]: https://img.shields.io/travis/async-rs/async-macros/master.svg?style=flat-square
[4]: https://travis-ci.org/async-rs/async-macros
[5]: https://img.shields.io/crates/d/async-macros.svg?style=flat-square
[6]: https://crates.io/crates/async-macros
[7]: https://img.shields.io/badge/docs-latest-blue.svg?style=flat-square
[8]: https://docs.rs/async-macros

[releases]: https://github.com/async-rs/async-macros/releases
[contributing]: https://github.com/async-rs/async-macros/blob/master.github/CONTRIBUTING.md
[good-first-issue]: https://github.com/async-rs/async-macros/labels/good%20first%20issue
[help-wanted]: https://github.com/async-rs/async-macros/labels/help%20wanted
