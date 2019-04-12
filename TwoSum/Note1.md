## Approach
### Approach 1: Brute force

The brute force approach is simple. Loop through each element $x$ and find if there is another value 
that equals to target - $x$.
 **Complexity Analysis**:
 * Time Complexity: $O*(n^2)$. For each element, we try to find its complement by looping throught the rest of array
 which takes $O(n)$ time. Therefore, the time complexity is $O(n^2)$
 * Space Complexity: $O(1)$