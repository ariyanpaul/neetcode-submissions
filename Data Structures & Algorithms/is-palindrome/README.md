Problem: Valid Palindrome

Approach: For this problem I did the reverse string approach where i took an empty string initially n = " ".
Then, filtered the input string to keep the alphanumeric characters (isalnum()) and then converted them to lower case and added them to the empty string 'n'.
Then, compared the clean string with the reversed string. IF it is a match output: True else, False.

Time complexity: O(n)
Space Complexity: O(n)
