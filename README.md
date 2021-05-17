# Sudoku Validator
This program validates whether a given sudoku board is valid or not.

## Algorithm :
1) Check if the rows and columns contain values 1-9, without repetition.
2) If any row or column violates this condition, the Sudoku board is invalid.
3) Check to see if each of the 9 sub-squares contains values 1-9, without repetition. If they do, the Sudoku board is valid; otherwise, it is invalid.

Language used : Python 3.8

## Sample Input :
![image](https://user-images.githubusercontent.com/80042740/116354768-83dd5700-a816-11eb-9a81-b6b5127c81d0.png)

## Sample Output :
![image](https://user-images.githubusercontent.com/80042740/116354835-9b1c4480-a816-11eb-8a85-d62e517bd292.png)
