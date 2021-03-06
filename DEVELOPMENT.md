# Prerequisites
- [rust] toolchain

[rust]: https://www.rust-lang.org

# Development
1. Make necessary changes.
1. Build. `make` to build, format and run [clippy], or `make build` to run build only.
1. Verify changes.
1. Run tests

[clippy]: https://github.com/rust-lang-nursery/rust-clippy

# Run tests
(Option 1) Refer [`Dockerfile`](Dockerfile) to install tests dependencies.
```sh
make test && make integration-test
```

(Option 2) With docker installed,
```sh
make test && make integration-test-docker
```
