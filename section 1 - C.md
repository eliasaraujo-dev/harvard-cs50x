# Section 1
- Variables
- Functions
- Loops
- Problem Set 1

## Part 1 - Variables and Types And Printing

### Variables
Create an integer named **calls** that gets the value 4.

int calls = 4;

Here we have an integer named **x** that gets the value 50.

int x = 50;

Calls gets 5.

calls = 5;

### Operators
int calls = 4;

calls = calls - 1;

calls = 3

### Getting input
This case, we try to get an input number, an integer number, we might want to use a function called **get_int**.

int calls = get_int("Calls: ")

### Functions
This is the tool that will allow us to grab this input from the user and then store it in our proverbial box.

### Return values
int calls = get_int(Calls: ")

"Calls: " ==>  get_int => 4

### Types and format codes

Numbers: int(%i), float (%f)

Text: char(%c), string(%s)

True/False: bool(%i)

### Hello, friends!
- Write a program that stores and prints out some information (like name, age, phone number)  
```C
#include <stdio.h>
#include <cs50.h>

int main (void)
{
    string name = get_string("What is your name? ");

    int age = get_int("What is your age? ");

    string hometown = get_string("What is your hometown? ");

    string number = get_string("What is your phone number? ");

    printf("My new friend's name is %s, %i, they are from %s and their phone number is %s\n", name, age, hometown, number);
}
```
## Part 2 - Breaking down loops and conditionals

Conditional with boolean expression ↓
```c
if (calls < 1)
{
  printf("Call more often!");
}
else
{
  printf("Thanks for calling!");
}
```
Conditional
