# C Standard Library

## Table

### String.h

| Name                                                 | Description                                                                                                                          | Return Values                                                                                                                                                                                                             |
| ---------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `int strcmp(const char *s1, const char *s2);`        | The `strcmp()` function compares the two strings `s1` and `s2`.                                                                      | <ul><li>0, if <code>s1</code> and <code>s2</code> are equal</li><li>a negative value if <code>s1</code> is less than <code>s2</code></li><li>a positive value if <code>s1</code> is bigger than <code>s2</code></li></ul> |
| `size_t strspn(const char *s, const char *accept);`  | The `strspn()` function calculates the length (in bytes) of the initial segment of `s` which consists entirely of bytes in `accept`. | The `strspn()` function returns the number of bytes in the initial segment of `s` which consist only of bytes from `accept`.                                                                                              |
| `size_t strcspn(const char *s, const char *reject);` | The `strcspn()` function calculates the length of the initial segment of `s` which consists entirely of bytes not in `reject`.       | The `strcspn()` function returns the number of bytes in the initial segment of `s` which are not in the string `reject`.                                                                                                  |

## Example

### String.h

#### strspn

#### strcspn
