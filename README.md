## Exercise about Exception Handling

In this Java exercise, a hotel reservation management program is created. The program reads initial reservation data, including room number, check-in, and check-out dates, displaying reservation details and duration. 
It allows updates to reservation dates with strict validation rules, such as changes only for future dates and the check-out date being after the check-in date.

This exercise was made exactly as in Nelio Alves' Java Course.

#### Solutions Overview:

#### Poor Approach (Solution 1):

Validation logic is directly implemented in the main program.
Lacks encapsulation; validation is not delegated to the reservation class.

#### Suboptimal Approach (Solution 2):

A method returning a string is used for validation.
Semantic issues with the operation; returning a string is not aligned with the purpose of updating a reservation.
Compromised readability with nested conditionals.

#### Good Approach (Solution 3):

Leveraging exception handling for validation.
Enhances semantic clarity and aligns with best practices.
Improved code structure and readability.
Delegates validation to constructors, emphasizing encapsulation.
