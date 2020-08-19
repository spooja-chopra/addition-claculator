# Addition

Scenario: Multiple numbers addition
  
  Given I have a calculator that's turned on.

  When I enter "number1"
  And I press "+" button
  And I press "number2"
  And I press "+" button
  And I press "number3"
   And  so on
   And I press "=" button"
  
  Then I see the "added sum of all numbers" as the result
  
  Scenario: Numbers can be negative
  Given I have a calculator that's turned on.
  When Negative number should be enter with "-" button and put in "()".
  
   I enter "number1"
  And I enter "+
  

Scenario: Length of each number
When 
  
  Then (state the effect)
Scenario: Add two numbers
Given I have a calculator that's turned on.

 When I enter "number1"
And I press "+" button
And I enter "number2"
And I press "=" button
Then I see the "added sum" as the result
Scenario: Subract two numbers
Given I have a calculator that's turned on.

 When Negative number should be enter with "-" button and put in "()".
   I enter "number1"
   And I press "-" button
   And I enter "number2"
   And I press "=" button
Then I see the "subtraction of two numbers" as the result
[10:58 AM] Vellal, Dattatreya (Guest)
    
# Addition
Scenario: Zero value multiplication
Given I have a calculator that's turned on.
When I enter "number1"
And I press "*"  button
And I enter "zero as number2"
And I  press "=" button
Then I see the "zero" as the  result

Scenario: Add two numbers
Given I have a calculator that's turned on.
 When I enter "number1"
And I press "+" button
And I enter "number2"
And I press "=" button
Then I see the "added sum" as the result
Scenario: Add more numbers
Scenario: Result is too large to display (or overrunning the limits)
Scenario: Numbers can be negative
Scenario: Numbers can be fraction
Scenario: Number can be irrational
Scenario: Length of each number
Scenario: If number1 or number2 is not entered
Scenario: If the number is real/complex
Scenario: If we are inbetween some operation


Scenario: Second number is 0 (friendly message)
Scenario: Fractional division
Scenario: First number is 0
Scenario: Denominator is greater than numberator
Scenario: Transitive property
Scenario: Final result is irrational
Scenario: Result exceeding limit of display
Scenario: Divisor is irrational (3/pi)
Scenario: When both numbers are imaginary (friendly message)
Scenario: Both are zero
Scenario: Result of denominator is zero (5/(3-3))
Scenario: both divident and divsors are non-number (friendly message)

[12:22 PM] Vellal, Dattatreya (Guest)
    
Scenario: Result overflow
Scenario: Signs of the numbers
Scenario: Zero value multiplication
Scenario: Decimal value multiplication
Scenario: Irrational value multiplication
Scenario: Simple multiplication
Scenario: Rational multiplication
Scenario: Decimal & integer multiplication
Scenario: More than two numbers multiplication
Scenario: Complex number multiplication
Scenario: Range of operand exceeds allowed limit
Scenario: Pressing "multiply button" multiple times
Scenario: Interleaving operators (Press *, then press /, then press +)
Scenario: Decimal value capping
​[12:24 PM] Shubham Gaikwad (Guest)
    

# Multiplication



Scenario: Multiply two number
Given I have a calculator that's turned on.



When I enter "number1"
And I press "*" button
And I enter "number2"
And I press "=" button

Then I see the "Product of the given 2 numbers” as the result



