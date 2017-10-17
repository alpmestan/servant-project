### Building

``` shell
# old method
$ cabal sandbox init && cabal install --only-dependencies
# then you can do cabal build, cabal run, etc.

# new method
$ cabal new-build
```
