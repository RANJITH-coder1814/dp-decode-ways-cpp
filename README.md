🧠 Approach

We use Dynamic Programming.

💡 Idea:
Let dp[i] represent the number of ways to decode the first i characters.
At each index:
Consider 1-digit decode (valid if not '0')
Consider 2-digit decode (valid if between 10 and 26)
⚠️ Edge Cases
'0' cannot be decoded alone
"10" and "20" are valid
If string starts with '0', return 0
