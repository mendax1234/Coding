# C Standard Library

## Table

### String.h

| Name                                                 | Description                                                                                                                          | Return Values                                                                                                                |
| ---------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------- |
| `size_t strspn(const char *s, const char *accept);`  | The `strspn()` function calculates the length (in bytes) of the initial segment of `s` which consists entirely of bytes in `accept`. | The `strspn()` function returns the number of bytes in the initial segment of `s` which consist only of bytes from `accept`. |
| `size_t strcspn(const char *s, const char *reject);` | The `strcspn()` function calculates the length of the initial segment of `s` which consists entirely of bytes not in `reject`.       | The `strcspn()` function returns the number of bytes in the initial segment of `s` which are not in the string `reject`.     |

## Example

### String.h

#### strspn

#### strcspn
