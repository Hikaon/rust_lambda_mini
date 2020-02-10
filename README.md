# rust_lambda_mini
Most basic implementation of AWS Lambda on Rust

Use as example or minimal template.
- Create your Rust function inside `fn my_handler`
- cargo build --release --target x86_64-unknown-linux-musl # or another unknown-linux, may be you will be lucky
- `zip -j rust.zip ./target/x86_64-unknown-linux-musl/release/bootstrap`

Upload zip into Lambda and start experimenting
