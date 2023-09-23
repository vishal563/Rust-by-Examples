
## Cheatseet for rust pkg manager cargo
| Command                                    | Description                                     |
|--------------------------------------------|-------------------------------------------------|
| `cargo new <project_name>`                 | Create a new Rust project                       |
| `cargo build`                              | Build the project                               |
| `cargo build --release`                    | Build a release (optimized) version of the project |
| `cargo run`                                | Build and run the project                      |
| `cargo test`                               | Run tests in the project                       |
| `cargo doc`                                | Generate documentation for the project          |
| `cargo clean`                              | Remove the target directory (clean build artifacts) |
| `cargo check`                              | Check the project for errors without building  |
| `cargo update`                             | Update dependencies to their latest versions   |
| `cargo install <package>`                  | Install a Rust package globally                 |
| `cargo uninstall <package>`                | Uninstall a globally installed Rust package    |
| `cargo search <query>`                     | Search for packages on crates.io               |
| `cargo publish`                            | Publish a package to crates.io                 |
| `cargo login`                              | Log in to your crates.io account for publishing |
| `cargo fix`                                | Automatically fix code using Clippy and Rustfmt |
| `cargo bench`                              | Run benchmarks defined in your project         |
| `cargo fmt`                                | Format code using Rustfmt                       |
| `cargo check --workspace`                  | Check the entire workspace for errors (for multi-package projects) |
| `cargo test --workspace`                   | Run tests for the entire workspace (for multi-package projects) |
| `cargo doc --workspace`                    | Generate documentation for the entire workspace (for multi-package projects) |
