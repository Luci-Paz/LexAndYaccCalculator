# LexAndYaccCalculator
LexAndYaccCalculator is a basic calculator utilizing lex and yacc

# Usage

- Need to have Lex, Yacc and Make installed
- Program works on UNIX terminals

### Running the calculator:
```Bash
user:fileLocation$ ./calc
331 Calculator
(type ? for help and . to exit)

>> [enter comands here]
```

### Command List: 

Assume A, B and C are all variables containing real numbers
```Bash
>> ?                      #Display the help menu

>> .                      #Exit the program

>> variableName           #Displays the value in a variable

>> variableName = A       #Sets a variable name to a real number value

>> A == B                 #Returns true or false depending on if the numbers are equal

>> A < B                  #Returns true or false if A is less than B

>> A > B                  #Returns true or false if A is greater than B

>> A + B                  #Returns the sum of A and B

>> A - B                  #Returns the difference of A and B

>> A * B                  #Returns A multiplied by B

>> A / B                  #Returns A divided by B

>> A % B                  #Returns the modulus of A mod B

>> A ^ B                  #Returns the value of A to the power of B

>> sqrt A                 #Returns the square root of A

>> sin A                  #Sin function of A in radians

>> cos A                  #Cos function of A in radians

>> tan A                  #Tan function of A in radians

>> -A                     #Negate the value of A (make it negative)

>> A + (B + C)            #Values in parentheses are copmuted first 
