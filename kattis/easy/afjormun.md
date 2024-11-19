# Afjörmun

## Question

{% embed url="https://open.kattis.com/problems/afjormun" %}

## Solution

### Idea

I believe the tricky part for this question is to deal with the input in C. The main algorithm is not that hard. It is just you upper the first letter and iterate all the way till the end, if it `isupper()`, then turn it to lower letter. Otherwise, just leave it as it is.

### Code

{% @github-files/github-code-block url="https://github.com/mendax1234/Coding-Problems/blob/main/kattis/afjormun/afjormun.c" %}

## Take-away

### Read a line in C

To read a line in C, it is "safer" to use `fgets()`. See more about it in [fgets](https://app.gitbook.com/s/KipySCGxC8NC1UpA24DS/lec-tut-lab-exes/lecture/lec-11-strcut-and-standard-i-o#fgets "mention").

{% code lineNumbers="true" %}
```c
if (fgets(line[i], MAX_LEN, stdin))
{
  line[i][strcspn(line[i], "\n")] = 0;
}
```
{% endcode %}

### Read an integer with newline

Suppose we input **an** integer with `\n`, to read it into a variable using `scanf()`, use the code below:

{% code lineNumbers="true" %}
```c
int a;
scanf("%d\n", &a);
```
{% endcode %}

The trailing `\n` is used for `scanf()` to consume/parse the newline character.
