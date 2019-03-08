# Assigment 1-Luis Suárez`s Strong Password

Luis Suárez joined a social networking site to stay in touch with his friends. The signup page required him to input a name and a password. 

However, the password must be strong. The website considers a password to be strong if it satisfies the following criteria:

-	Its length is at least 6.
-	It contains at least one digit.
-	It contains at least one lowercase English character.
-	It contains at least one uppercase English character.
-	It contains at least one special character. The special characters are: !@#$%^&*()-+

She typed a random string of length n in the password field but wasn't sure if it was strong. Given the string she typed, can you find the password rules that he couldn`t keep?

Note: Here's the set of types of characters in a form you can paste in your solution:

```
numbers = "0123456789"
lower_case = "abcdefghijklmnopqrstuvwxyz"
upper_case = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
special_characters = "!@#$%^&*()-+"
```
 
## Input Format

The second line contains a string consisting of n characters, the password typed by Luis Suárez. Each character is either a lowercase/uppercase English alphabet, a digit, or a special character.

## Constraints

-	1 <= n <= 20

## Output Format

Print the following rules that he must keep:

-	Must contain at least 6 more characters.
-	Must contain at least 1 digit.
-	Must contain at least 1 lowercase English character.
-	Must contain at least 1 uppercase English character.
-	Must contain at least 1 special character.

If he keeps all rules for strong password, print “Thank you for signing up!”.
