# Kiss-Zig Repo
This repo packages the Zig programming language for Kiss Linux.

## Usage
Add this repo to the start of `KISS_PATH`. This is so that the included `LLVM` package takes priority over the `LLVM` belonging to the main repos, which is incompatible with `Zig`.

### Note

This repo builds LLVM with all default targets to allow Zig to cross-compile. This is the officially supported configuration by Zig. If you don't mind giving up the official support and cross-compiling, you may use the Zig packages in the community repo instead.
