# A Stack of Gold

Question: [Here](https://open.kattis.com/problems/astackofgold)

## Solution

### Idea

This problem is a bit interesting. The solution is implemented in $$O(N)$$. Here we just assume all the stacks are tungsten. And then we loop through every stack (cuz we take different number of coins from every stack). And during each iteration, we add the number of coins times the difference between the weight of gold coins and tungsten coins. If the weight is equal to the input weight. Then this stack is what we want.

### Code

