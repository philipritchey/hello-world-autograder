# hello-world-autograder
an example autograded assignment

## Problem Description

Write the class `Hello`, which

* when compiled and run, prints `hello, world!`
* contains the method `public static boolean isPrime(long n)`, which
  * determines whether the argument is a prime number
    * a prime is a positive integer with exactly two divisors: 1 and itself
      * :warning: 1 is not prime because it only has 1 divisor

## Assignment Setup

### prepare upload to gradescope
`make`

creates the file `autograder.zip`

### upload to gradescope
1. create a programming assignment
2. upload `autograder.zip`
3. base image os: Ubuntu
4. base image version: 22.04
5. base image variant: JDK 17
6. update autograder
7. test autograder
8. check settings
   * dates, times
   * submission methods
   * ignored files
   * container specifications
   * timeout
