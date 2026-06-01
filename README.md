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
string,int,float,character;
```
#include <stdio.h>
int main()
{
    printf("welcome to india");
    return 0;
}

#include <stdio.h>
int main()
{
    float num;
    scanf("%f",&num);
    printf("%.2f",num);
    return 0;
}

#include <stdio.h>
int main()
{
    int var1;
    int var2;
    scanf("%d",&var1);
    scanf("%d",&var2);
    int result = var1%var2;
    printf("Remainder of %d and %d=%d",var1,var2,result);
    return 0;
}

#include <stdio.h>
int main()
{
    int var;
    scanf("%d",&var);
    printf("Character of ASCII Value %d is %c",var,var);
    return 0;
}
```
# Output:

<img width="1032" height="397" alt="image" src="https://github.com/user-attachments/assets/d501d1a0-8c93-48b2-9632-aa80aee6631d" />

<img width="1300" height="450" alt="image" src="https://github.com/user-attachments/assets/236efab7-2f38-4607-bcfd-cffa37eecce9" />

<img width="1212" height="432" alt="image" src="https://github.com/user-attachments/assets/7d03e8ae-7891-4050-b505-ed3015e15bb4" />

<img width="1362" height="563" alt="image" src="https://github.com/user-attachments/assets/69375a95-c2d1-4e01-ae0e-212168c2b503" />

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
```
#include <stdio.h>
int main()
{
    float PI = 3.14159;
    int Days = 7;

    printf("%f",PI);
    printf("%d",Days);

    return 0;
}
```
# Output:

<img width="820" height="406" alt="image" src="https://github.com/user-attachments/assets/7355db1b-9af5-4feb-9801-c8e89e3f5d26" />

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
```
#include <stdio.h>
int main()
{
    int var;
    scanf("%d",&var);
    printf("Character of ASCII Value %d is %c",var,var);
    return 0;
}

#include <stdio.h>
int main()
{
    int var1;
    int var2;
    scanf("%d",&var1);
    scanf("%d",&var2);
    int result = var1%var2;
    printf("Remainder of %d and %d=%d",var1,var2,result);
    return 0;
}

#include <stdio.h>
int main()
{
    float num;
    scanf("%f",&num);
    printf("%.2f",num);
    return 0;
}

#include <stdio.h>
int main()
{
    printf("welcome to india");
    return 0;
}
```
# Output:

<img width="1300" height="450" alt="image" src="https://github.com/user-attachments/assets/52f9a950-5b1a-403a-b1b2-8a84617b4731" />

<img width="1212" height="432" alt="image" src="https://github.com/user-attachments/assets/726b5c37-ee88-4595-a5ce-5fa81508cd23" />

<img width="1363" height="564" alt="image" src="https://github.com/user-attachments/assets/02d2c0a1-b6c4-4ec9-b0b1-8dbe4331d931" />

<img width="1032" height="397" alt="image" src="https://github.com/user-attachments/assets/f213c209-e162-4619-abcc-bde37ec98508" />

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
```
#include <stdio.h>
int main()
{
    int num1, num2,num3;
    scanf("%d %d %d",&num1,&num2,&num3);
    int sum = num1 + num2 + num3;
    printf("Sum is:%d",sum);
    return 0;
}

#include <stdio.h>
int main()
{
    int num1, num2;
    scanf("%d %d",&num1,&num2);
    int sum = num1 - num2;
    printf("Sum is:%d",sum);
    return 0;
}

#include <stdio.h>
int main()
{
    int num1, num2,num3;
    scanf("%d %d %d",&num1,&num2,&num3);
    int sum = num1 * num2 * num3;
    printf("Sum is:%d",sum);
    return 0;
}

#include <stdio.h>
int main()
{
    int num1, num2;
    scanf("%d %d",&num1,&num2);
    int sum = num1 / num2;
    printf("Sum is:%d",sum);
    return 0;
}

#include <stdio.h>
int main()
{
    int num1, num2;
    scanf("%d %d",&num1,&num2,);
    int sum = num1 & num2;
    printf("Sum is:%d",sum);
    return 0;
}

#include <stdio.h>
int main()
{
    int num1, num2;
    scanf("%d %d",&num1,&num2);
    int sum = num1 | num2;
    printf("Sum is:%d",sum);
    return 0;
}

#include <stdio.h>
int main()
{
    int num1, num2;
    scanf("%d %d %d",&num1,&num2);
    int sum = num1 >> num2 ;
    printf("Sum is:%d",sum);
    return 0;
}

```
# Output:

<img width="871" height="468" alt="image" src="https://github.com/user-attachments/assets/8db7a0e1-cfc2-4604-b20d-49d9957eafa5" />

<img width="680" height="245" alt="image" src="https://github.com/user-attachments/assets/1ae85676-9892-45b8-ab4d-d4be5b389fa1" />

<img width="700" height="273" alt="image" src="https://github.com/user-attachments/assets/d8eebe05-d72f-4606-8741-6976a7041191" />

<img width="688" height="255" alt="image" src="https://github.com/user-attachments/assets/32564542-5286-4b0e-9171-324192657fd5" />

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
```
#include <stdio.h>
int main()
{
    char array[100];
    fgets (array,sizeof(array),stdin);
    
    for (int i = 0; array[i] !='\0'; i++)
    {
        if (array[i] >= 'a' && array[i] <= 'z')
        {
            printf("True");
        }
        else{
            printf("False");
        }
    }
}
#include <stdio.h>
int main()
{
    char array[100];
    fgets (array,sizeof(array),stdin);
    
    for (int i = 0; array[i] !='\0'; i++)
    {
        if (array[i] >= '0' && array[i] <= '9')
        {
            printf("True");
        }
    }
    return 0;
}

#include <stdio.h>
int main()
{
    char a;
    scanf("%c,&a);
    if (a == 'a' || a== 'i')
    {  
        printf("True");
    }
}
  
```


# Output:


<img width="705" height="117" alt="image" src="https://github.com/user-attachments/assets/589a4b27-a210-4c84-9e35-9355ad492284" />

<img width="696" height="172" alt="image" src="https://github.com/user-attachments/assets/5864e820-70c7-4bf3-87cd-7d01ec3428aa" />

<img width="697" height="312" alt="image" src="https://github.com/user-attachments/assets/597fab1a-90bf-4551-9ecf-004b114f7e46" />


# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


