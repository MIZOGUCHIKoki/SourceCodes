# Description of each file

* `arrayTest.c`: This is for checking array-related behavior.
* `roulette.c`: This is a roulette file.
* `roulette_old.c`: This is a legacy roulette file.

# Usage of `roulette.c`

1. Compile: 
```
$ gcc roulette.c -o roulette
```
2. Execute:
```
$ ./roulette [first argument] [second argument]
```
  1. The first argument is the number of populations to be extracted.
  2. The second argument is the number of extracts.

  For example, you should enter the following command to extract 20 people from 30 people.
```
$ ./roulette 30 20
```
  Of course, the second argument is less than or equal to the first argument.

