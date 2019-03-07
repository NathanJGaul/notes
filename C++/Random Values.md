# Random Values

## `rand`

`int rand (void);`
returns a pseudo-random integral number in the range of 0 and `RAND_MAX`, where `RAND_MAX` is a constant defined in `<cstdlib>`

## `srand`
`void srand (unsinged int seed);`
sets the seed of the pseudo-random number generator initialization, everytime a new seed is initialized a new sequence of pseudo-random numbers can be expected

- e.g. `srand(time(NULL));`

> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIxMjgzMDE0Ml19
-->