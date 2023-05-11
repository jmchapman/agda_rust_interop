current usage


Dependencies:
* agda2rust
* nightly build of rust


Usage:
```
$ cargo build

[Remove the following from the generated Test.rs file in target/...
* the attributes at the start
* the main function at the end
]

$ cargo run
```