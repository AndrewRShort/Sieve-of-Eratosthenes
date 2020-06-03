# Sieve-of-Eratosthenes
Jack code that finds primes numbers using the Sieve of Eratosthenes algorithm

  Output all prime numbers <= n using the "Sieve of Eratosthenes" algorithm 

  The output is nicely formatted, with columns of numbers that line up.

  Multiple pages of output are handled by asking the user to hit any key
  before the next page is shown.

  Compile this Jack code with the built-in compiler, or your compiler, 
  then run the program in the VMEmulator.

  Make sure in the VMEmulator to:
    (1) set Speed to "Fast"
    (2) set Animation to "No animation"

  n is limited by the 14k (14336) Hack computer heap size, less other minor heap allocations.

  If you are using the built-in Memory class, you can set n very close to 14k.
  If you are using your own Memory class, you may have a slightly 
  lower limit if your heap manager does not implement defragmentation.
  The code imposes a limit of 14000 which should always work.
