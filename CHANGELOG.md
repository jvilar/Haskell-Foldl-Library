1.4.3

* Add `Control.Scanl.scanr`
* Increase upper bound on `mwc-random`

1.4.2

* Add `Semigroupoid` instance for `Fold`
* Increase upper bound on `contravariant` and `profunctors`

1.4.1

* Add `Control.Scanl`
* Drop support for GHC 7.8 and older

1.4.0

* BREAKING CHANGE: Change type of `premapM` to accept a monadic function

1.3.7

* Add `groupBy`

1.3.6

* Documentation improvements

1.3.5

* Add `Choice` instance for `Fold`

1.3.4

* Add `prefilter` and `prefilterM`

1.3.3

* Add back the old `vector` as `vectorM`

1.3.2

* Compatibility with `Semigroup` becoming a super-class of `Monoid`
* Fix `asin` for `Fold`

1.3.1

* Fix `asin` for `FoldM`

1.3.0

* BREAKING CHANGE: Change `vector` to be a pure `Fold` (which is faster, too!)

1.2.5

* Add support for folding new containers: `hashSet`, `map`, and `hashMap`
* Add `prescan`/`postscan` which generalize `scan` to `Traversable` types

1.2.4

* Add `lazy` folds for `Text` and `ByteString`
* Documentation fixes and improvements

1.2.3

* Add `lookup`

1.2.2

* Add numerically stable `mean`, `variance`, and `std` folds
* Add `Control.Foldl.{Text,ByteString}.foldM`
* Add `foldOver`/`foldOverM`

1.2.1

* Performance improvements
* Re-export `filtered`

1.2.0

* Breaking change: Fix `handles` to fold things in the correct order (was
  previously folding things backwards and also leaking space as a result).  No
  change to behavior of `handlesM`, which was folding things in the right order
* Breaking change: Change the `Monoid` used by `Handler`/`HandlerM`
* Add `folded`

1.1.6

* Add `maximumBy` and `minimumBy`

1.1.5

* Increase lower bound on `base` from `< 4` to `< 4.5`

1.1.4

* Increase upper bound on `comonad` from `< 5` to `< 6`

1.1.3

* Increase upper bound on `profunctors` from `< 5.2` to `< 5.3`
* Add `mapM_`, `hoists`, `purely`, and `impurely`

1.1.2

* Add `lastN`, `randomN`, `sink`, and `duplicateM`
* Add `Comonad` instance for `Fold`
* Add `Profunctor` instance for `FoldM`

1.1.1

* Increase upper bound on `vector` from `< 0.11` to `< 0.12`

1.1.0

* Breaking change: Rename `pretraverse`/`pretraverseM` to `handles`/`handlesM`
* Add `Handler`
* Export `EndoM`

1.0.11

* Add `Profunctor` instance for `Fold`

1.0.10

* Add `random` and `_Fold1`

1.0.9

* Increase upper bound on `primitive` from `< 0.6` to `< 0.7`

1.0.8

* Add `revList`

1.0.7

* Add `Num` and `Fractional` instances for `Fold`/`FoldM`
* Add `count` fold for `Text` and `ByteString`

1.0.6

* Add `pretraverse` and `pretraverseM`

1.0.5

* Add `lastDef`

1.0.4

* Increase upper bounds on `transformers` from `< 0.4` to `< 0.6`
* Add `nub`, `eqNub`, and `set`

1.0.3

* Add `scan`, `generalize`, `simplify`, and `premapM`

1.0.2

* Add `list` and `vector` folds
* Add `fold` function for `Text` and `ByteString`

1.0.1

* Add support for `ByteString` and `Text` folds
* Add `Monoid` instance for `Fold`/`FoldM`

1.0.0

* Initial release
