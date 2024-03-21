# Intuition
Noted the desired output was just the name column, so I would need to focus only on the conditionals and data types.

# Approach
> So the __*SELECT name FROM Customer*__ statement was very easy to get, since the output only required the name column returned. 

The __*WHERE referee_id != 2 OR referee_id IS NULL;*__ statement I was trying to figure out if there was a way to make it shorter, but no success. 

After plenty of trying, I decided to write two parts of what I was trying to return: __*WHERE referee_id != 2 AND referee_id IS NULL;*__ Note that at first attempt, I tried using __"AND"__, which did not returned me what was required. Then, I opted for __"OR"__ which I obtained the desired output.

# Code
```
# Write your MySQL query statement below
SELECT name FROM Customer
WHERE referee_id != 2 OR referee_id IS NULL;
```
![image](https://github.com/Lucas-Nascimento-Tech/Leetcode-problem-solutions/assets/94206149/c2851e54-d953-40c1-a138-e72c7cc3627f)
