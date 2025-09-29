# The Rust Books

[![TRPL](https://github.com/aidigproject/rsdocs-actions/actions/workflows/trpl.yaml/badge.svg)](https://github.com/aidigproject/rsdocs-actions/actions/workflows/trpl.yaml)
[![tlborm](https://github.com/aidigproject/rsdocs-actions/actions/workflows/tlborm.yaml/badge.svg)](https://github.com/aidigproject/rsdocs-actions/actions/workflows/tlborm.yaml)
[![rustwasm](https://github.com/aidigproject/rsdocs-actions/actions/workflows/rustwasm.yaml/badge.svg)](https://github.com/aidigproject/rsdocs-actions/actions/workflows/rustwasm.yaml)
[![rust-embedded](https://github.com/aidigproject/rsdocs-actions/actions/workflows/rust-embedded.yaml/badge.svg)](https://github.com/aidigproject/rsdocs-actions/actions/workflows/rust-embedded.yaml)
[![async-book](https://github.com/aidigproject/rsdocs-actions/actions/workflows/async-book.yaml/badge.svg)](https://github.com/aidigproject/rsdocs-actions/actions/workflows/async-book.yaml)
[![perf-book](https://github.com/aidigproject/rsdocs-actions/actions/workflows/perf-book.yaml/badge.svg)](https://github.com/aidigproject/rsdocs-actions/actions/workflows/perf-book.yaml)
[![edition-guide](https://github.com/aidigproject/rsdocs-actions/actions/workflows/edition-guide.yaml/badge.svg)](https://github.com/aidigproject/rsdocs-actions/actions/workflows/edition-guide.yaml)
[![cheats.rs](https://github.com/aidigproject/rsdocs-actions/actions/workflows/cheats-rs.yaml/badge.svg)](https://github.com/aidigproject/rsdocs-actions/actions/workflows/cheats-rs.yaml)
[![rust-course](https://github.com/aidigproject/rsdocs-actions/actions/workflows/rust-course.yaml/badge.svg)](https://github.com/aidigproject/rsdocs-actions/actions/workflows/rust-course.yaml)
[![learning-rust-by-practice](https://github.com/aidigproject/rsdocs-actions/actions/workflows/rust-by-practice.yaml/badge.svg)](https://github.com/aidigproject/rsdocs-actions/actions/workflows/rust-by-practice.yaml)
[![the-rust-edition-guide](https://github.com/aidigproject/rsdocs-actions/actions/workflows/edition-guide.yaml/badge.svg)](https://github.com/aidigproject/rsdocs-actions/actions/workflows/edition-guide.yaml)
[![actix-web](https://github.com/aidigproject/rsdocs-actions/actions/workflows/actix-web.yaml/badge.svg)](https://github.com/aidigproject/rsdocs-actions/actions/workflows/actix-web.yaml)
[![cargo](https://github.com/aidigproject/rsdocs-actions/actions/workflows/cargo.yaml/badge.svg)](https://github.com/aidigproject/rsdocs-actions/actions/workflows/cargo.yaml)
[![rust-guide](https://github.com/aidigproject/rsdocs-actions/actions/workflows/rust-guide.yaml/badge.svg)](https://github.com/aidigproject/rsdocs-actions/actions/workflows/rust-guide.yaml)

## Requirements

Building the book requires [mdBook], ideally the same version that
rust-lang/rust uses in [this file][rust-mdbook].

[mdBook]: https://github.com/rust-lang-nursery/mdBook
[rust-mdbook]: https://github.com/rust-lang/rust/blob/master/src/tools/rustbook/Cargo.toml

## Book List(China mirror) - auto build with github actions

| Name | Language | Comment(fork from) |
|:- |:- |:- |
|[The Rust Programming Language(2021 edition)](http://docs.aidig.co/trpl/en) | en | [@rust-lang](https://github.com/rust-lang/book)|
|[Rust 程序设计语言(2021 edition)](http://docs.aidig.co/trpl/zh) | zh | [@KaiserY](https://github.com/KaiserY/trpl-zh-cn)|
|[The Little Book of Rust Macros](http://docs.aidig.co/tlborm/en/) | en | [@Veykril](https://github.com/Veykril/tlborm) |
|[Rust 宏小册](http://docs.aidig.co/tlborm/zh/) | zh | [@zjp-CN](https://github.com/zjp-CN/tlborm) |
|[The Rust and WebAssembly Book](http://docs.aidig.co/rustwasm/en/) | en | [@rustwasm](https://github.com/rustwasm/book) |
|[The Embedded Rust Book](http://docs.aidig.co/rust-embedded/en/) | en | [@rust-embedded](https://github.com/rust-embedded/book) |
|[Asynchronous Programming in Rust](http://docs.aidig.co/async-book/en/) | en | [@rust-lang](https://github.com/rust-lang/async-book) |
|[The Rust Performance Book](http://docs.aidig.co/perf-book/en/) | en | [@rust-lang](https://github.com/nnethercote/perf-book) |
|[The Rust Edition Guide](http://docs.aidig.co/edition-guide/en/) | en | [@rust-lang](https://github.com/rust-lang/edition-guide) |
|[Learn Rust with examples](http://docs.aidig.co/rust-by-example/en/) | en | [@rust-lang](https://github.com/rust-lang/rust-by-example) |
|[通过例子学 Rust](http://docs.aidig.co/rust-by-example/zh/) | zh | [@rust-lang-cn](https://github.com/rust-lang-cn/rust-by-example-cn) |
|[Rust Language Cheat Sheet](http://docs.aidig.co/cheats.rs/en/) | en | [@ralfbiedert](https://github.com/ralfbiedert/cheats.rs) |
|[Rust 语言备忘清单（简体中文）](http://docs.aidig.co/cheats.rs/zh/) | zh | [@kingfree](https://github.com/kingfree/cheats.rs/) |
|[A Rust Cookbook](http://docs.aidig.co/rust-cookbook/en/) | en | [@rust-lang-nursery](https://github.com/rust-lang-nursery/rust-cookbook) |
|[Rust语言圣经 (The Course)](http://docs.aidig.co/rust-course/zh/) | zh | [@sunface](https://github.com/sunface/rust-course) |
|[Learning Rust By Practice](http://docs.aidig.co/rust-by-practice/en/) | en | [@sunface](https://github.com/sunface/rust-by-practice) |
|[Rust 练习实践](http://docs.aidig.co/rust-by-practice/zh/) | zh | [@sunface](https://github.com/sunface/rust-by-practice/blob/master/zh-CN/src/why-exercise.md) |
|[Rust Cargo 官书（非官方翻译)](http://docs.aidig.co/cargo/zh/) | zh | [@chinanf-boy](https://github.com/chinanf-boy/cargo-book-zh) |
|[The Cargo Book](http://docs.aidig.co/cargo/en/) | en | [@rust-lang](https://github.com/rust-lang/cargo) |
|[actix-web 中文文档](http://docs.aidig.co/actix-web/zh/) | zh | [@zzy](https://github.com/zzy/actix-web-zh-cn) |
|[Rust 实践指南](http://docs.aidig.co/rust-guide/zh/) | zh | [@sunface](https://github.com/zzy/rust-guide) |
|[Comprehensive Rust](http://docs.aidig.co/comprehensive-rust/en/) | en | [@google](https://github.com/google/comprehensive-rust) |
|[Rustup: the Rust toolchain installer](http://docs.aidig.co/rustup/en/) | en | [@rust-lang](https://github.com/rust-lang/rustup) |
|[PyO3 user guide](http://docs.aidig.co/pyo3/en/) | en | [@PyO3](https://github.com/PyO3/pyo3) |
|[Learn Rust Easy](http://docs.aidig.co/Learn-rust-easy/zh/) | zh | [@令狐壹冲](https://github.com/RustyCab/LearnRustEasy) |

* Embedded Rust on Espressif ([en](http://docs.aidig.co/std-training/en/) / [zh](http://docs.aidig.co/std-training/zh/))
* The Rust on ESP Book ([en](http://docs.aidig.co/rust-on-esp/en/) / [zh](http://docs.aidig.co/rust-on-esp/zh/))
* impl Rust for ESP32 ([en](http://docs.aidig.co/esp32-book/en/) / zh)

## Notes

* Run every day at 6:00 AM UTC
* Triggered manually

## Contribute

* Use [issues](https://github.com/aidigproject/rsdocs-actions/issues) for everything
