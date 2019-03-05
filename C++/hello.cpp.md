# hello.cpp

```
#include <iostream>

int main()
{
	std::cout << "Hello World!\n";
}
```

## Line by Line

### `#include <iostream>`
- importing/including libraries

### `int main()`
- the main function that all C++ programs need, returns an integer

### `{`
- the opening bracket of the main function
- indicates the begining of the code block that is the function

### `std::cout << "Hello World!\n";`

- the meat of the program
- `std::cout` is the "**c**haracter **out**put stream" in the `std` namespace
- `<<`, in this context, is the overloading of the left shift operator
	- it is equivalent to `put(std::cout, "Hello, World!\n");`




> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTkwMDMyMTEwMSwtMTMzOTA2Mzg1OF19
-->