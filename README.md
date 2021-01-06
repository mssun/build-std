An example to demonstrate build-std in Cargo.

```
$ rustup install nightly-2021-01-05
$ __CARGO_TESTS_ONLY_SRC_ROOT=`pwd`/rust cargo +nightly-2021-01-05 build --target custom-target.json -Zbuild-std=core,compiler_builtins,alloc,std -vv
```
