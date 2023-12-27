```rust
fn main() {
    struct Chaewon {
        name: String,
        study: [String; 3],
        tools: [String; 3],
    }

    let chaewon = Chaewon {
        name: String::from("Chaewon"),
        study: [String::from("Rust"), String::from("C++"), String::from("TypeScript")],
        tools: [String::from("VSCode"), String::from("IntelliJ"), String::from("neovim")],
    };
}
```
