# mini-starcoinvm
a standalone starcoin vm used in layer2 

no I/O for checking syscall only


```shell
cargo build --release --no-default-features --features from_mock --target=x86_64-unknown-linux-musl
```

Using musl for static link only