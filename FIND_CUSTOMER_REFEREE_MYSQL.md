# Intuition
<!-- Noted the desired output was just the name column, so I would need to focus only on the conditionals and data types. -->

# Approach
<!--So the *SELECT name FROM Customer* statement was very easy to get, since the output only required the name column returned. The *WHERE referee_id != 2 OR referee_id IS NULL;* statement I was trying to figure out if there was a way to make it shorter, but no success. After plenty of trying, I decided to write two parts of what I was trying to return: *WHERE referee_id != 2 AND referee_id IS NULL;* Note that at first attempt, I tried using "AND", which did not returned me what was required. Then, I opted for "OR" which I obtained the desired output.-->

# Code
```
# Write your MySQL query statement below
SELECT name FROM Customer
WHERE referee_id != 2 OR referee_id IS NULL;
```
