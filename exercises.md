# Sample exercises

## Simple




## Intermediate

### Guessing game where the computer get smarter.
What Animal am I thinking of?

Make a guessing game where the computer continuously becomes smarter after every guess.  
Here is an example run: (The computer is guessing what animal you're thinking of.)
```
Computer: Does the animal you're thinking of have legs?
 Player: Yes
 Computer: Is it a dog?
 Player: Yes
 Computer: I win! Do you want to play again?
 Player: Yes
 Computer: Does the animal you're thinking of have legs
 Player: Yes
 Computer: Is it a dog?
 Player: No
 Computer: I give up. What was your animal?
 Player: Horse
 Computer: Type a question which the answer is yes for Dog but No for Horse
 Player: Does it live in a house?
 Computer: Do you want to play again?
 Player: Yes
 Computer: Does the animal you're thinking of have legs?
 Player: Yes
 Computer: Does it live in a house?
 Player: No
 Computer: Is it a horse?
 Player: No
 Computer: I give up
```
 
### Validate "numeric" input. (try and except and return)

Complete the function definition for “validate_numeric" a function that makes sure the user entered a “legal” number.
Floating point numbers and integers are both allowed.

Your function should:
* return the number (if valid). 
* return it as the type entered (int or float)
* return None if it is not a valid number
 

You will need to use the “try” and “except” and “return” commands to complete this.
(Look them up.)

```
def validate_numeric(num_str):
	… your code here …
	return converted_num  # it it’s a number, or
	return None   # if it’s invalid
```

```
# Main
user_input = input('Enter a number ')
result = validate_numeric(user_input)

if type(result) == type(1):
    print('The number entered is an integer. The value is: ' + str(result) )
elif type(result) == type(1.1):
    print('The number entered is floating point. The value is: ' + str(result) )
elif (result) == None:
    print('The number entered is not valid. The value you entered is: "' + user_input + '"')

exit()
```
