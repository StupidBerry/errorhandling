# Error Handling
The purpose of this smart contract is to create a simple mechanism that checks whether you are eligible to vote or not.

# Description
In my project, I created a simple Solidity smart contract named VotingEligibility to demonstrate basic error handling using require(), assert(), and revert() statements. The contract takes in user age as parameter and checks whether the user is eligible to vote or not . Require statement is used to ensure that the age entered is not 0 . Assert statement is used to check a condition which we know cannot be false , we checked the age to be less than 150 as we know that the age of a normal human cannot exceed 150 years. The event "agecheck" displays a message that the user is eligible to vote if the age is greater than or equals to 18. And lastly the revert statement is used to display an error message if the age entered is less than 18 displaying the error message that "You are not eligible to vote".
