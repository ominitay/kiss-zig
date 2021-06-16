# Kiss-Zig Repo
This repo packages the Zig programming language for Kiss Linux.

## Usage
Add this repo to the start of `KISS_PATH`. This is so that the included `LLVM` package takes priority over the `LLVM` belonging to the main repos, which is incompatible with `Zig`.

### Note

This repo builds `LLVM` with all default targets to allow `Zig` to cross-compile. This is the officially supported configuration by `Zig`. The community repo package is out-of-date and possibly broken, thanks to changes introduced in `Zig` meaning that the `LLVM` package must be built with all default targets. The only way this may be fixed is by the official `LLVM` package being changed to include all targets. If this doesn't happen, the community package will be dropped.
