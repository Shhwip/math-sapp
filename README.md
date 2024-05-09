# Math Sapp
A fork of floooh/sokol-samples to learn sokol. All non-sapp samples removed to simplify the repo.

first run

```sh
./fips setup emscripten
./fips set config sapp-webgl2-wasm-ninja-debug
```

to build, run the following

```sh
./fips make math-sapp
./fips run math-sapp
```

this will be slow the first time as it needs to clone all the dependencies

if you want to build all of the sapp samples run the following

```sh
./fips build
./fips list targets
./fips run {target}
```
