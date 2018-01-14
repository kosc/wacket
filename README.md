# wacket

Racket to WebAssembly "compiler".

## Quick Start

1. Install [wabt][wabt]
2. Install [racket][racket]
3. `$ make`
4. `$ python -m SimpleHTTPServer 3001`
5. `$ <browser> http://localhost:3001/index.html`
8. Change math expression in the `input.rkt` file and `make` again.

[wabt]: https://github.com/WebAssembly/wabt
[racket]: https://racket-lang.org/
