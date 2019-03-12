# Even Fibonacci numbers

```haskell
fibs :: [Integer]
fibs = 1 : 2 : zipWith (+) fibs (tail fibs)
```

```haskell

```