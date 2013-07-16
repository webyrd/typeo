typeo
=====

Simple DSL for writing even simpler type inferencers.

Uses cKanren's new `templateo` constraint, which is essentially a lazy, declarative version of Prolog's `copy_term/2`.

Requires the latest Racket cKanren: https://github.com/calvis/cKanren

To run, `cd` into this directory, then run:

`raco test typeo.rkt`
