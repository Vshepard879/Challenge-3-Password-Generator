# Password Generator

## Description
Worked on by Vincent Shepard

AS AN employee with access to sensitive data
I WANT to randomly generate a password that meets certain criteria
SO THAT I can create a strong password that provides greater security

## Acceptance Criteria
- GIVEN I need a new, secure password
- WHEN I click the button to generate a password
- Then I am presented with a series of prompts for password criteria
- WHEN prompted for password criteria
- THEN I select which criteria to include in the password
- WHEN prompted for the length of the password
- THEN I choose a length of at least 8 characters and no more than 128 characters
- WHEN asked for character types to include in the password
- THEN I confirm whether or not to include lowercase, uppercase, numeric, and/or special characters
- WHEN I answer each prompt
- THEN my input should be validated and at least one character type should be selected
- WHEN all prompts are answered
- THEN a password is generated that matches the selected criteria
- WHEN the password is generated
- THEN the password is either displayed in an alert or written to the page

## Changes that were made
- Created different sets of variables for upper/lower case numbers, numbers and symbols to be used for password generation
- set the character sets of each variable to an array
- also added a blank array to be appended to from the user's choices
- created a while/if/else loop to ensure at least 1 character type is chosen 
- created a function to determine password length
- made sure the initial prompt started after clicking the Generate Password button
- added prompts to let user determine the types of characters used in the password 
- ensured the password is written to the page.
- added descriptives to the js code added for ease of viewing 
- created a quality README.md




## Tools used

- Javascript



## Screenshot
`![ScreenShot](/assets/images/screenshot.png)
