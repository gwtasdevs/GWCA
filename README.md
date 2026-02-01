# GWCA (TAS version)

This Rust script modifies `gwca.dll` so that minipets can be targeted.
This repo runs on a schedule every 10 mins to check for new toolbox releases, modifies gwca.dll and publishes it to github.

## Prerequisites
- Rust: https://rust-lang.org/tools/install/

## Usage
- Place `gwca.dll` in the root folder
- Run `cargo run` in the terminal
- `gwca.dll` will be overwritten with the modified version
