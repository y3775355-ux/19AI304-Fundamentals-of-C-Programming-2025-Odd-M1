# 19AI304-Fundamentals-of-C-Programming-2025-Odd-M1
# IAPR-1- Module 1 - FoC
## 1. Implementation of basic C programs using Literals,Consonants, Variables, Data types.
## 2. Implementation of different categories of operators.
# Ex.No:1
  Build a C program to demonstrate the usage of different types of literals: integer, float, character, and string.  
# Date : 
# Aim:
To build a C program that prints integer, float,character, and string literals on the console using the printf() function.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Inside the main() function, use printf() to display each literal along with its size in bytes using sizeof() :
  
   3.1 Integer literal (e.g., 10) using `%d`
   
   3.2 Float literal (e.g., 3.14) using `%f`
   
   3.3 Character literal (e.g., 'A') using `%c`
   
   3.4 String literal (e.g., "Hello C") using `%s`
   
### Step 4: 
   Stop
# Program:
#include <stdio.h>
int main() {
    int num = 100;
    float pi = 3.14;
    char grade = 'A';
    char message[] = "Hello, World!";
    printf("Integer Literal: %d\n", num);
    printf("Float Literal: %.2f\n", pi);
    printf("Character Literal: %c\n", grade);
    printf("String Literal: %s\n", message);
    return 0;
}
# Output:
<img width="1373" height="426" alt="image" src="https://github.com/user-attachments/assets/d50e0b9d-8d53-4e78-b4a8-96e3c0229ebd" />
# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:2
  Build a C program to display the value of a macro constant and a constant variable.
# Date : 
# Aim:
  To build a C program that demonstrates the use of macro constants and constant variables.
# Algorithm:
### Step 1:
  Start  
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Define a macro constant `PI` with value `3.14159` using `#define`.
### Step 4: 
   Inside `main()`:
   
   4.1 Declare a constant integer variable `DAYS`
   
   4.2 Initialize it with the value `7`
   
### Step 5:  
  Use `printf()` to display the values of `PI` and `DAYS`.     
### Step 6:  
  Stop
# Program:
#include <stdio.h>

#define MAX 100

int main() {
    const int value = 50;

    printf("Macro Constant: %d\n", MAX);
    printf("Constant Variable: %d\n", value);

    return 0;
}
# Output:
<img width="1235" height="509" alt="image" src="https://github.com/user-attachments/assets/dcab2f28-41df-4b3c-8c05-2c4e49cba6d7" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:3
  Build a C program to demonstrate the use of different data types such as int, float, double, and char, and display their values using printf().
# Date : 
# Aim:
  To build a C program that declares variables of various data types—integer, float, double, and character—initializes them, and prints their values on the screen.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Inside main(), declare and initialize variables of types int, float, double, and char.
### Step 4: 
   Display their values using printf().
### Step 5:    
   Stop
# Program:
#include <stdio.h>

int main() {
    int a = 10;
    float b = 5.5;
    double c = 123.456;
    char d = 'X';

    printf("Integer: %d\n", a);
    printf("Float: %.2f\n", b);
    printf("Double: %.3lf\n", c);
    printf("Character: %c\n", d);

    return 0;
}
# Output:
<img width="1259" height="503" alt="image" src="https://github.com/user-attachments/assets/3557d103-6aa5-4896-aa3a-b8c832f338e6" />
# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.
# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:4
  Build a C program to perform arithmetic and bitwise operations on two integers entered by the user. The program should display: Arithmetic operations: addition, subtraction, multiplication, division, and remainder. Bitwise operations: AND, OR, XOR, left shift, right shift, and NOT.
# Date : 
# Aim:
  To build a C program that takes two integers as input and demonstrates the arithmetic and bitwise operations, displaying the results of each operation.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Declare two integer variables a and b.
### Step 4: 
   Prompt the user to enter two integers and read the input using scanf().
### Step 5:    
   Perform arithmetic operations on a and b:
   #### Sum (a + b)
   #### Difference (a - b)
   #### Product (a * b)
   #### Quotient (a / b)
   #### Remainder (a % b)
### Step 6: 
  Perform bitwise operations on a and b:
  #### AND (a &amp; b)
  #### OR (a | b)
  #### XOR (a ^ b)
  #### Left shift (a << b)
  #### Right shift (a >> b)
  #### Bitwise NOT of a (~a) and b (~b)
### Step 7:   
  Display the results of all operations using printf().
### Step 8:   
  Stop
# Program:
    int a, b;

    scanf("%d %d", &a, &b);

    printf("Addition: %d\n", a + b);
    printf("Subtraction: %d\n", a - b);
    printf("Multiplication: %d\n", a * b);
    printf("Division: %d\n", a / b);
    printf("Remainder: %d\n", a % b);

    printf("Bitwise AND: %d\n", a & b);
    printf("Bitwise OR: %d\n", a | b);
    printf("Bitwise XOR: %d\n", a ^ b);
    printf("Left Shift (a << 1): %d\n", a << 1);
    printf("Right Shift (a >> 1): %d\n", a >> 1);
    printf("Bitwise NOT (~a): %d\n", ~a);

    return 0;
}
# Output:
<img width="1283" height="659" alt="image" src="https://github.com/user-attachments/assets/e52ee99c-a1e9-48b9-b9b0-a5d2fabe74a2" />
# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:5
  Develop a C program to check whether a given character is a vowel, consonant, digit, or special symbol using the ternary operator.
# Date : 
# Aim:
  To develop and implement a C program that classifies a character as a vowel, consonant, digit, or special symbol using the ternary operator.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Input a character ch from the user.
### Step 4: 
   Check if ch is a digit ('0' to '9').
   
   If true → Print "Digit" → Go to Step 8.
   
   If false → Go to Step 5.
   
### Step 5:    
   Check if ch is an alphabet letter ('A' - 'Z' or 'a' – 'z').
   
   If true → Go to Step 6.
   
   If false → Go to Step 7.
   
### Step 6: 
   Check if ch is a vowel (a, e, i, o, u or A, E, I, O, U).
   
   If true → Print "Vowel" → Go to Step 8.
   
   If false → Print "Consonant" → Go to Step 8.
   
### Step 7:   
   Print "Special Symbol".
### Step 8:   
  Stop
# Program:
    char ch;
    scanf("%c", &ch);

    (ch >= '0' && ch <= '9') ?
        printf("Digit") :
    ((ch >= 'A' && ch <= 'Z') || (ch >= 'a' && ch <= 'z')) ?
        ((ch=='A'||ch=='E'||ch=='I'||ch=='O'||ch=='U'||ch=='a'||ch=='e'||ch=='i'||ch=='o'||ch=='u') ?
            printf("Vowel") :
            printf("Consonant")) :
        printf("Special Symbol");

    return 0;
}
# Output:
<img width="1590" height="591" alt="image" src="https://github.com/user-attachments/assets/2bb91c2e-2081-4b0d-b86d-f6e46f3d4df6" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


