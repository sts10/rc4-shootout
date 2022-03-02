# RC4 Variants PRNG Shootout
Benchmark performance of RC4 and its variants.

To build, execute:

    $ cargo build --release

Then run one of the binaries:

    $ ./target/release/rc4

Benchmarks on my Intel Core i7-8650U CPU @ 1.90GHz:

| PRNG   | MBps   |
|--------|:------:|
| RC4    | 429.13 |
| RC4A   | 679.78 |
| RC4+   | 430.68 |
| VMPC   | 327.31 |
| Spritz |  79.79 |
