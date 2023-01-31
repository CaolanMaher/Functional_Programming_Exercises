# Caolan Maher Haskell Functional Programming Exercises

## Exercise 1
Write a function named add1 that takes an Int and returns an Int that is
one greater than its input. For example, if we compute add1 5, we should get
6. If you want to write a type signature for add1, it would be

`add1 :: Int -> Int`

## Solution

    add1 :: Int -> Int
    add1 x = x + 1
    
## Exercise 2
Write a function:

`always0 :: Int -> Int`

The return value should always be 0.

## Solution

    always0 :: a -> Int
    always0 _ = 0
    
## Exercise 3
Write a function:

`subtract' :: Int -> Int -> Int`

that takes two numbers (that is, Ints) and subtracts them

## Solution

    subtract' :: Int -> Int -> Int
    subtract' x y = x - y
    
## Exercise 4
Write a function

`addmult :: Int -> Int -> Int -> -> Int`

that takes three numbers. Let’s call them p, q, and r. addmult should add p
and q together and then multiply the result by r.

## Solution

    addmult :: Int -> Int -> Int -> Int
    addmult p q r = (p + q) * r
    
## Exercise 5
Write a function

`greaterThan0 :: Int -> String`

That returns the String ”Yes!” if the number is greater than 0, and ”No!”
otherwise.

## Solution

    greaterThan0 :: Int -> String
    greaterThan0 x
        | x > 0 = "Yes!"
        | otherwise = "No!"
        
## Exercise 6
Look at the function

`pushOut :: Int -> Int`
