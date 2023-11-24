# 0x00. Fix my code

[0-fizzbuzz.py](./0-fizzbuzz.py)

- A script that prints `Fizz` for numbers which are a multiple of 3, `Buzz`
  for numbers which are a multiple of, 5 and `FizzBuzz` for numbers that are
  multiplies of both 3 and 5.
- `Bug:` The problem with this script was that it printed `Fizz` for
  numbers that are a multiple of 3 and 5, instead of printing `FizzBuzz`.

[1-print_square.js](./1-print_square.js)

- A program that prints a square with the character #, in JavaScript.
  The size of the square must be the first argument of the program.
- `Bug`: The problem with the program was it converted the size argument in
  base 16.

[2-sort.rb](./2-sort.rb)

- A ruby program that sorts given numbers as arguments.
- `Bug`: The problem was when inserting a number into the sorted list, it
  inserted them at `i-1` instead of `i`, which in the former case it will
  cause numbers that should have come front go to the end.

[3-user.py](./3-user.py)

- A python class that tests a User class defined in the script.
- `Bug`: The setter for password attribute, assigned a valid password to
  `_password` instead of `__password`. And second, the `is_valid_password`
  method converted the md5 value of `pwd` to upper when comparing it with
  `__password`.

[4-delete_dnodeint/](./4-delete_dnodeint/)

- A C implementation of a doubly linked list.
- `Bug`: The problem is found in the `delete_dnodeint_at_index` function. When
  deleting a node at a valid index, it did not connect the previous and
  subsequent nodes of the node to be deleted.
