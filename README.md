An example to demonstrate build-std in Cargo.

```
$ __CARGO_TESTS_ONLY_SRC_ROOT=`pwd`/rust cargo +nightly build --target custom-target.json -Zbuild-std=core,compiler_builtins,alloc,std -vv
```
