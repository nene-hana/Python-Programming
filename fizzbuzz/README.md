# FizzBuzz

A simple Python program that checks numbers from **1 to 100**.

## Logic

* Divisible by both **3 and 5** → `fizzbuzz`
* Divisible by **3** → `fizz`
* Divisible by **5** → `buzz`
* Otherwise → `undefined`

## Concepts Used

* `for` loop
* `range()`
* Modulo operator `%`
* `if / elif / else`
* Logical operator `and`
* f-strings

## Important

The **FizzBuzz condition must come first**, because a number like `15` is divisible by both 3 and 5. If we check `% 3` first, `15` would be caught as `fizz`.
