rust-augeas
===========

This is a fork of https://github.com/panicbit/rust-augeas .

Right now, it works only on Linux, due to its dependence on `open_memstream`, which in turn is necessary to abstract over augeas' `aug_srun`.
