# Experiment 3 – Create an Application for Guessing a Number using Common Programming Constructs of Rust  

<H3>ENTER YOUR NAME:</H3>  
<H3>ENTER YOUR REGISTER NO:</H3>  
<H3>EX.NO.3</H3>  
<H3>DATE:</H3>  

<H1 ALIGN =CENTER> Guessing a Number using Common Programming Constructs of Rust </H1>  

## AIM:  
To build a simple interactive Rust program that lets a user guess a randomly chosen number while demonstrating variables, loops, conditionals, functions, pattern matching, and basic error handling.  

## EQUIPMENTS REQUIRED:  
- Hardware – PCs  
- Software – Visual Studio Code (Version 1.104.0)  
- Rust Installation  

## RELATED THEORETICAL CONCEPT:  

*Guessing Game Concept in Rust:*  
- Uses **variables** to store guesses and the secret number.  
- Uses **loops** for repeated guessing until the correct number is found.  
- Uses **conditionals & pattern matching** to compare the guess with the secret.  
- Uses **error handling** for invalid user inputs.  

*Libraries Used:*  
- `std::cmp::Ordering` → to compare the guessed number with the secret number.  
- `std::io` → to read user input.  
- `rand` crate → to generate a random secret number.  

## ALGORITHM:  
STEP 1: Start the program. <BR>  
STEP 2: Import the required libraries: `std::cmp::Ordering`, `std::io`, and `rand`. <BR>  
STEP 3: Define the `main` function. <BR>  
STEP 4: Print the message *“I’m thinking of a number between 1 and 100…”*. <BR>  
STEP 5: Generate and assign the secret number. <BR>  
STEP 6: Start an infinite loop (`loop`). <BR>  
STEP 7: Prompt the user to enter a guess. <BR>  
STEP 8: Read the input as a string. <BR>  
STEP 9: Convert the input into an integer (`u32`).  
&nbsp;&nbsp;• If conversion fails, show an error message and continue the loop. <BR>  
STEP 10: Print the guessed number. <BR>  
STEP 11: Compare the guess with the secret number using `cmp`:  
&nbsp;&nbsp;• If guess < secret → print *“Too low!”*  
&nbsp;&nbsp;• If guess > secret → print *“Too high!”*  
&nbsp;&nbsp;• If guess == secret → print *“WELL! You guessed it right”*, and break the loop. <BR>  
STEP 12: End the program. <BR>  

## PROGRAM:  
```


// Type Your Code here



````
## OUTPUT :

## RESULT :
