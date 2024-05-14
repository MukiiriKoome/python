This technique is used for finding subarrays in an array that satisfy given conditions.
Maintain a subset of items as your window and resize and move that window within the larger list until you find a solution.
This technique is a subset of Dynamic Programming.
Time complexity:0(n)
Space Complexity:0(1)

You can identify Sliding window problems amongst subarray/substring related questions.
Given a string s, find the length of the longest 
substring
 without repeating characters.

 

Example 1:

Input: s = "abcabcbb"
Output: 3
Explanation: The answer is "abc", with the length of 3.
Example 2:

Input: s = "bbbbb"
Output: 1
Explanation: The answer is "b", with the length of 1.
Example 3:

Input: s = "pwwkew"
Output: 3
Explanation: The answer is "wke", with the length of 3.
Notice that the answer must be a substring, "pwke" is a subsequence and not a substring.
 

Constraints:

0 <= s.length <= 5 * 104
s consists of English letters, digits, symbols and spaces.