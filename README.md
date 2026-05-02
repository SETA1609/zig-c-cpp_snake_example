# zig-c-cpp_snake_example

Snake game project with a Zig-first codebase (about 80%) and a small C++ layer (about 20%) for OpenGL windowing and rendering.

## Project layout

```
.
├── build.zig
└── src/
    ├── main.zig
    ├── game.zig
    ├── input.zig
    ├── wasm.zig
    ├── c/
    └── cpp/
        ├── window.hpp
        ├── window.cpp
        ├── renderer.hpp
        ├── renderer.cpp
        └── effects.cpp
```

## Notes

- Zig hosts the game loop, gameplay state, and input.
- C++ provides the OpenGL-facing pieces (window/context, renderer, effects).
- The C++ layer should expose a minimal C ABI surface for Zig to call.

## Build

```bash
# TODO: add Zig build steps
```

## Run

```bash
# TODO: add run command
```

## Controls

- TODO: list keyboard/gamepad controls

## Roadmap

- TODO: gameplay features
- TODO: rendering features
