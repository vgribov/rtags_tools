# USAGE

```sh
cd build
make_and_trace
update_rtags ${PWD%/build}
```

In order to use a cross compiler, export `CROSS_COMPILE` environment variable
with the right prefix, e.g.

```sh
CROSS_COMPILE=x86_64-linux-musl- make_and_trace
```
