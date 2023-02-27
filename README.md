#Omar's baby GREP

`cargo run [query] [filename]` should return all instances of `query` in `filename`, as long as the file is in the root directory of the project. Of course, you can also just `cargo build` and use the binary in `target` as your application.

This is built with the help of [Chapter 12 of the Rust Programming Language Book](https://doc.rust-lang.org/stable/book/ch12-00-an-io-project.html). Compared to C, Rust seems like a lot more to learn compile-time, and a lot less headache run-time, with a bunch of modern conveniences (inferred typing, closures, generics, etc.). Excited to keep learning! 
