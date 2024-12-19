# The Rust Programming Language

This repository is for studying Rust.

https://doc.rust-jp.rs/book-ja/ch01-02-hello-world.html

## How to Execute

### build
```shell
docker build -t rust-the-book:latest .
```

### compile and execute
```shell
PWD=$(pwd) docker run -v $PWD/practice:/root/practice rust-the-book bash -c 'cd /root/practice && rustc hello_world.rs && ./hello_world'
```