# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
~~~
#include <stdio.h>
#include <stdlib.h>
#include <time.h>
int main()
{
    int n, min, max, i;
    srand(time(0));
    printf("Enter number of random numbers: ");
    scanf("%d", &n);
    printf("Enter minimum value: ");
    scanf("%d", &min);
    printf("Enter maximum value: ");
    scanf("%d", &max);
    printf("Random numbers within range:\n");
    for(i = 0; i < n; i++)
    {
        printf("%d\n", (rand() % (max - min + 1)) + min);
    }
}

~~~
# OUTPUT:

<img width="1917" height="1198" alt="Screenshot 2026-10-30 185632" src="https://github.com/user-attachments/assets/9651e759-ca3c-4004-be19-adc4d67d1d28" />


# RESULT:
Thus,the implementation of Pseudorandom Number is executed successfully.


