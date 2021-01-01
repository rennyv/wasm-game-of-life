[![Build Actions Status](https://github.com/rennyv/wasm-game-of-life/workflows/Build/badge.svg)](https://github.com/rennyv/wasm-game-of-life/actions)
# Game of Life

Simple demo of wasm in Rust creating the Conway's Game of Life 

## Tools

- Install `rustup`, `rustc`, and `cargo`
  - [Follow instructions here](https://www.rust-lang.org/tools/install)
- Node with npm
  - [Follow instructions here](https://www.npmjs.com/get-npm)
- Generated with cargo-generate
  - `cargo install cargo-generate`
- Testing you need firefox installed
  - (Ubuntu) `sudo apt install firefox`
## Setup

1. `wasm-pack build`
2. `cd www`
3. `npm install`
4. `npm run start`

## Testing
1. `wasm-pack test --firefox --headless`