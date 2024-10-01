# 2024年秋冬季操作系统训练营

## Cargo项目结构

```
.
├── src/
│   ├── main.rs
│   ├── lib.rs
│   ├── mod1.rs
│   ├── mod2.rs
│   └── mod1_submod/
│       └── mod1_submod.rs
├── target/
│   ├── debug/
│   └── release/
└── Cargo.toml
```

crate 是 Rust 在编译时最小的代码单位，crate 有两种形式：二进制项和库。

包（package）是提供一系列功能的一个或者多个 crate，一个包会包含一个 Cargo.toml 文件，阐述如何去构建这些 crate。

包中可以包含至多一个库 crate(library crate)，但可以包含任意多个二进制 crate(binary crate)。

