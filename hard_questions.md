# Problem 1
Compare dictionaries  'using recursions'

```
def dict_compare(*args): 
return True/False

```
 Using recursion, return a list of all combinations of dictionaries that are identical to each other for all combinations of dictionaries provided.



# Problem 2
 Matching regular expression

Given an input string s and a pattern p, implement regular expression matching with support for '.' and '*' where:

'.' Matches any single character.​​​​
'*' Matches zero or more of the preceding element.


```
Input: s = "aa", p = "a"
Output: false
because "a" does not match the entire string "aa".
```

# Problem 3 
 Roman to Integer  ( Vise versa)
Roman numerals are represented by seven different 
```
Input: s = "III"
Output: 3
Explanation: III = 3.

```

# Problem 4
Finding the Friday 

We have a given date and we have to find whether it is Friday 
 or 
We have given year and find out how many friday comes
on 1st of month

```
solver(from: datetime.date, to: datetime.date)
return is it a friday

```


# Problem 5
Pyramid problem find the maximum total 

By starting at the top of the triangle below and moving to adjacent numbers on the row below, the maximum total from top to bottom is 23 

```
input : solver(pyramid)
output : max of the numbers in the pyramid
```


# Problem 6 
Letter Combinations of a Phone Number

convert the numbers into text by looking at the phone's  dial pad

eg  2: ABC

```
def fun("23")
     return  ["ad","ae","af","bd","be","bf","cd","ce","cf"]

```

# Problem 7

Convert the binary search tree into a doubly linked list 


 ```
 input : solver(binary search tree) :
output : doubly linked list
 ```

 
# Problem 8
 Longest Common Prefix

 Write a function to find the longest common prefix string amongst an array of strings.

```
Input: strs = ["flower","flow","flight"]
Output: "fl"
```

# Problem 9
 Os operations 

 Advance operations related to the Os
 ```
 def solver() :
      'creating this particular file in this particular locations '

 ```

# Problem 10
Eight Queen problem 

given is a chess board and we have to find the perfect way to add eigth queens such that they will not kill each other 

# Problem 11
Using list/dictionary

Find the difference or intersection / union between the strings


```
def solver(string): 
    return difference or intersection / union in string 

```


# Problem 12
Cataloging a list of lists using recursion

takes a deeply nested list of lists and flattens it out, ignores any dict elements, and returns a dictionary where the key is value and the value is the count of each item in the flattened list. Use recursion to flatten the list.

```
def solver(list)
 return a flatten list 

```

# Problem 13
Largest Product in a Grid
What is the greatest product of four adjacent numbers in the same direction (up, down, left, right, or diagonally) in the  grid?

```
def solver(p,q) :
  return greatest product of n
```

# Problem 14

 Write a program to solve a Sudoku puzzle by filling the empty cells.
```
 Input: 
 board = [["5","3",".",".","7",".",".",".","."],["6",".",".","1","9","5",".",".","."],[".","9","8",".",".",".",".","6","."],["8",".",".",".","6",".",".",".","3"],["4",".",".","8",".","3",".",".","1"],["7",".",".",".","2",".",".",".","6"],[".","6",".",".",".",".","2","8","."],[".",".",".","4","1","9",".",".","5"],[".",".",".",".","8",".",".","7","9"]]

 Output: [["5","3","4","6","7","8","9","1","2"],["6","7","2","1","9","5","3","4","8"],["1","9","8","3","4","2","5","6","7"],["8","5","9","7","6","1","4","2","3"],["4","2","6","8","5","3","7","9","1"],["7","1","3","9","2","4","8","5","6"],["9","6","1","5","3","7","2","8","4"],["2","8","7","4","1","9","6","3","5"],["3","4","5","2","8","6","1","7","9"]]

```