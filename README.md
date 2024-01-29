# todo.fasm

To-Do Web Application in flat assembler for Linux x86_64

Features:
- Completely self-contained single static executable (depends only on Linux x86_64 kernel);
- Includes its own simple HTTP Server listening to port 6969 (hardcoded);
- Frontend works without JavaScript.

## Quick Start

Install [flat assembler](https://flatassembler.net/)

```console
$ fasm ./todo.asm
$ chmod +x ./todo
$ ./todo
open browser at http://localhost:6969/
```
## Credits

Build using [tsoding's code](https://github.com/tsoding)
