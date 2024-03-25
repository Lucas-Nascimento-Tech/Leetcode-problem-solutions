# Intuition
The desired outcome was a single column to be returned, so I would need only to work (harder) on the conditional statement.

# Approach
> The __*WHERE*__ statement I was trying to figure out if there was a way to make it shorter, but no success. 
> Then, I decided to write it in two parts of what I was trying to return: __*WHERE referee_id != 2__ 
Followed by: __*AND referee_id IS NULL;*__

# Code
```
SELECT product_id FROM Products 
WHERE low_fats = 'Y' AND recyclable = 'Y'

```

![image](https://github.com/Lucas-Nascimento-Tech/Leetcode-problem-solutions/assets/94206149/983457b9-62e0-465f-936b-d49277136930)
