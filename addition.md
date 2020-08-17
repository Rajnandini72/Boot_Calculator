# Addition

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
