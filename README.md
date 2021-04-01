# Kiss-Zig Repo
This repo packages the Zig programming language for Kiss Linux.

## Usage
Add this repo to the start of `KISS_PATH`. This is so that the included `LLVM` package takes priority over the `LLVM` belonging to the main repos, which is incompatible with `Zig`.