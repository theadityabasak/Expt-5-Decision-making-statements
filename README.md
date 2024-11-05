# Expt-5-Decision-making-statements
# App used: VS Code
# Theory
Decision-making is a concept that allows the execution of different code paths based on conditions. The if and else statements are primary constructs used for decision-making in C++. These constructs enable the implementation of conditional logic. They help us check whether a condition is true and if it is, then the block inside the same is executed.
# Algorithm
# Quadrant Checker
Start

Initialize:

Declare two integer variables num1 and num2.
Input:

Ask the user to enter the X-axis coordinate and store it in num1.
Ask the user to enter the Y-axis coordinate and store it in num2.
Decision Making (using if-else statements):

If num1 > 0 and num2 > 0:
Print "The point is in the first quadrant."
Else If num1 < 0 and num2 > 0:
Print "The point is in the second quadrant."
Else If num1 < 0 and num2 < 0:
Print "The point is in the third quadrant."
Else If num1 > 0 and num2 < 0:
Print "The point is in the fourth quadrant."
Else If (num1 == 0 and num2 != 0) or (num1 != 0 and num2 == 0):
Print "The point is on the axis."
Else:
Print "The point is at the origin."
End

# Positive or Negative
Start

Initialize:

Declare a float variable num.
Input:

Ask the user to enter a number and store it in num.
Decision Making (using if-else statements):

If num > 0:
Print "The num is POSITIVE."
Else:
Print "The num is NEGATIVE."
End

# grade Checker
Start

Initialize:

Declare a char variable a.
Input:

Ask the user to enter a character and store it in a.
Decision Making (using if-else statements):

If a is one of the following vowels (both lowercase and uppercase):
'a', 'e', 'i', 'o', 'u', 'A', 'E', 'I', 'O', 'U':
Print "a is a vowel."
Else:
Print "a is a consonant."
End

# Conclusion
From This experiment We have learned and understand the use of Decision Making Statements If-else Statements in the program.
