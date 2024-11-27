# Rust & WebAssembly dev environment

This repo contains a dev container configuration to try out Rust & WebAssembly
development without installing all the tools necessary to compile Rust to WASM.

Open this workspace in VS Code and run the "Dev Containers: Reopen in Container"
task.

This repo also contains a bootstrapped wasm-pack project. Check that everything
works by running

```sh
wasm-pack build -t web
```

This should put a bunch of wasm and js/ts files into the pkg folder.
