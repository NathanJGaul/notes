# Random Values

## `rand`

`int rand (void);`
returns a pseudo-random integral number in the range of 0 and `RAND_MAX`, where `RAND_MAX` is a constant defined in `<cstdlib>`

e.g.
```
v1 = rand() % 100;         // v1 in the range 0 to 99
v2 = rand() % 100 + 1;     // v2 in the range 1 to 100
v3 = rand() % 30 + 1985;   // v3 in the range 1985-2014 
```

## `srand`
`void srand (unsinged int seed);`
sets the seed of the pseudo-random number generator initialization, everytime a new seed is initialized a new sequence of pseudo-random numbers can be expected

e.g.
`srand(time(NULL));`

> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIwMDA0MTkyMjldfQ==
-->