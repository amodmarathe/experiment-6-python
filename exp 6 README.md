Amod Marathe 
PRN - 25070123073
AIM - study of conditional statements in python
    
Conditional statements in Python are used to execute certain blocks of code based on specific conditions. These statements help control the flow of a program, making it behave differently in different situations.
If Conditional Statement-
If statement is the simplest form of a conditional statement. It executes a block of code if the given condition is true.
If else Conditional Statement
If Else allows us to specify a block of code that will execute if the condition(s) associated with an if or elif statement evaluates to False. Else block provides a way to handle all other cases that don't meet the specified conditions.

 algortihm 1
Start
Take an integer input from the user.
If the number is greater than 0, print "positive".
Else if the number is less than 0, print "negative".
Else, print "zero".
Stop
 
 algortihm 2
 Start
Take an integer input from the user.
Calculate the remainder of the number divided by 2 (using %).
If the remainder is 0, print "even".
Else, print "odd".
Stop.

Algorithm 3: Find the Largest of Three Numbers
Start
Read three numbers from the user
Compare the first number with the other two
If the first number is largest, print it
Else compare the second and third numbers
Print the largest number
Stop

Algorithm 4: Check whether a Year is Leap Year
Start
Read a year from the user
Check if the year is divisible by 4 and not divisible by 100
Or check if the year is divisible by 400
If any condition is true, print Leap Year
Otherwise, print Not a Leap Year
Stop


algortihm 5
 Grade Calculation 
 Start
 Take marks as a float input.
 If marks $\ge 90$, print "Grade A".
 Else if marks $\ge 80$, print "Grade B".
 Else if marks $\ge 70$, print "Grade C".
 Else if marks $\ge 60$, print "Grade D".
 Stop

algorithm 6
Start
Input day, month, and year separately.
Check if the month is a 31-day month, 30-day month, or February.
If Month is 12 and Day is 31, reset Day and Month to 1 and increment Year.
If Day is less than the month's maximum, increment Day.
If Day is at the month's maximum, reset Day to 1 and increment Month.
Handle February by checking leap year conditions to determine if the max day is 28 or 29.
Print the updated date.
Stop.

algorithm 7
Start 
Input basic salary.
If salary $\le 10,000$: HRA = 20%, DA = 80%.
Else if salary $\le 20,000$: HRA = 25%, DA = 90%.
Else: HRA = 30%, DA = 95%.
Calculate Gross Salary = $Basic + (HRA \times Basic) + (DA \times Basic)$.
Print Gross Salary.
Stop

algorithm 8
Start
Input annual income. 
If income $\le 250,000$: Tax = 0.
Else if income $\le 500,000$: Tax = 5% of amount over 250,000.
Else if income $\le 1,000,000$: Tax = Fixed tax from lower bracket + 20% of amount over 500,000.
Else: Tax = Fixed tax from lower brackets + 30% of amount over 1,000,000.P
rint total tax.
Stop

algorithm 9
Start
Input a character.
Create a list containing all vowels (upper and lower case).
If the character exists in the vowel list, print "it is a vowel"
Else, print "it is a consonant".
Stop.

algorithm 10
Start 
Define a string "python is easy".
Use the split() function to break the string into a list of words.
Assign each word to a separate variable ($a, b, c$).
Print each variable.
Stop

algorithm 11
Start
Input date in dd/mm/yyyy format.
Split the string by / and convert parts to integers.
Determine max_days for the given month (accounting for leap years in February).
If month/day values are out of realistic bounds, print "Invalid".
If day is the last day of the month:
If month is 12, set day=1, month=1, year=year+1.
Else, set day=1, month=month+1.
Else, increment day by 1.
Print the incremented date.
Stop

concluison - we succesfully implemented if loop



we
