Problem: Two Sum

Approach: I used brute force method where two nested loops are used to check evry possible pair of numbers.
For each index [i] the inner loop starts from i+1 so, the same element doesn't repeat twice.
if num[i] + num[j] equals target value then return both indices.

Time complexity:O(n^2)

Space complexity: O(1)
