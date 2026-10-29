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
    int n, i;

    printf("Enter the number of random numbers to generate: ");
    scanf("%d", &n);

 
    srand(time(NULL));

    printf("\nPseudorandom numbers:\n");

    for (i = 0; i < n; i++)
    {
        printf("%d ", rand());
    }

    printf("\n");

    return 0;
}
~~~
# OUTPUT:

<img width="692" height="660" alt="Screenshot 2026-10-29 092151" src="https://github.com/user-attachments/assets/34ef4233-8d5b-4898-a35b-c116c3fc3354" />

# RESULT:
Thus,the implementation of Pseudorandom Number is executed successfully.


