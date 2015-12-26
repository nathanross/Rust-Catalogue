#Better rust

An "awesome"-type list (like [awesome rust](https://github.com/kud1ing/awesome-rust)) focused on the most essential references and resources. Focused on knowledge and tools-as-community-conventions rather than tools per se.

## Out of the Box

Understand out-of-the-box lang and libstd features better to make better use of them in your code!

Because these articles are not explicitly stated to be maintained by a core team, assume some of the information may be incomplete or out of date and make use of them accordingly.

* [NRC's Rust Design Patterns repo](https://github.com/nrc/patterns) (extremely helpful!)
* [Daniel Keep's iter cheat sheet](https://danielkeep.github.io/itercheat_baked.html)
* [Using the option type effectively](blog.8thlight.com/uku-taht/2015/04/29/using-the-option-type-effectively.html)
* [Periodic table of rust types](http://cosmic.mearie.org/2014/01/periodic-table-of-rust-types/)

## Community idioms

Extremely popular patterns in the community for solving common problems

[throw!](https://github.com/daboross/rust-throw)

## Community resources

* [```play.rust-lang.org``` (rust playground)](https://play.rust-lang.org/)
* [```rust-lang.org```](https://rust-lang.org)
  * nightly
    * [reference](https://doc.rust-lang.org/nightly/reference.html) | [libstd reference](https://doc.rust-lang.org/nightly/std/index.html) | [rustdoc ref](https://doc.rust-lang.org/nightly/book/documentation.html)
    * learn: [The Rust Book](https://doc.rust-lang.org/nightly/book/) | [Rust By Example](http://rustbyexample.com/)
* [```crates.io```](https://crates.io)
  * [```cargo``` documentation](http://doc.crates.io/)
* [```rustdocs.org```](https://rustdocs.org)
* [```areweideyet.org``` - are we ide yet](https://areweideyet.com) - "awesome list" of various ide plugins for rust support

## Essential tools - (almost) Universally useful

* [```racer```](https://github.com/phildawes/racer) - code completion for rust
* [```rust clippy```](https://github.com/Manishearth/rust-clippy) - lints for common mistakes and potential performance improvements
* [```rustfmt```](https://github.com/rust-lang-nursery/rustfmt) - Automatically format code according to the Rust ecosystem default style.
* [```cargo edit```](https://github.com/killercup/cargo-edit) - edit cargo dependencies from command line (ala ```npm```)
* [```cargo watch```](https://github.com/passcod/cargo-watch) - recompile source code as it changes
* [```cargo check```](https://github.com/rsolomo/cargo-check) - instead of compiling source code, just get errors and warnings (less time/processor usage)

## Shout-out to

* [```cargo-script```](https://github.com/DanielKeep/cargo-script)
* [```libhoare```](https://github.com/nrc/libhoare) - high-powered design by contract in rust (until we get dependent types) ([why as macros](https://www.reddit.com/r/rust/comments/2akn0y/libhoare_pre_and_postconditions_for_rust/ciwjr1g))
* [```power assert```](https://github.com/gifnksm/power-assert-rs)
