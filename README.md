
<img width="5400" height="2383" alt="Code Karaoke-min" src="https://github.com/user-attachments/assets/b93e02e6-6468-4a00-9a9e-a00bc0e4cb0f" />


#TEAM NAME:VIBECODERS
# level-2-code-karaoke
Level 2 questions for code karaoke event, there are 2 questions write the program and test it with examples in those questions and upload in fork 
# Question 1:
1.Tow Sum:
Given an array of integers nums and an integer target, return indices of the two numbers such that they add up to target.
You may assume that each input would have exactly one solution, and you may not use the same element twice.
You can return the answer in any order.
 
 
# Example 1:
Input: nums = [2,7,11,15], target = 9
Output: [0,1]
Explanation: Because nums[0] + nums[1] == 9, we return [0, 1].

# Example 2:
Input: nums = [3,2,4], target = 6
Output: [1,2]

# Example 3:
Input: nums = [3,3], target = 6
Output: [0,1]

# CODE:
```
def twoSum(nums,target):
    for i in range(len(nums)):
        for j in range(i+1,len(nums)):
            if nums[i]+nums[j]==target:
                return[i,j]
print(twoSum([4,5,6,7],9))
```
# OUTPUT:
```
[0, 1]
```
PICTURE:
QUESTION 1:
<img width="440" height="206" alt="Screenshot 2025-11-08 112114" src="https://github.com/user-attachments/assets/7c5559e2-1a08-46e5-a648-197e556ae66e" />


# Question 2:
1. Palindrome Number:

Given an integer x, return true if x is a palindrome, and false otherwise.
 
# Example 1:
Input: x = 121
Output: true
Explanation: 121 reads as 121 from left to right and from right to left.
# Example 2:
Input: x = -121
Output: false
Explanation: From left to right, it reads -121. From right to left, it becomes 121-. Therefore it is not a palindrome.
# Example 3:
Input: x = 10
Output: false
Explanation: Reads 01 from right to left. Therefore it is not a palindrome.


# CODE:
```
def isPalindrome(x):
    return str(x)==str(x)[::-1]
print(isPalindrome(198))
```
# OUTPUT:
```
False
```
PICTURE:
<img width="379" height="134" alt="Screenshot 2025-11-08 112124" src="https://github.com/user-attachments/assets/c1f7822c-ae01-4cad-81b7-940b775a1cc5" />
