# Multiples of 3 and 5

This problem can be solved with one simple line in GHCi:

```haskell
sum [i | i <- [1..999], i `mod` 3 == 0 || i `mod` 5 == 0]
```
