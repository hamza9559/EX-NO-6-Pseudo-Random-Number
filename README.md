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
```c
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() {
    int n, i;

    printf("Pseudo-Random Number Generation using Standard Library\n");

    srand(time(0));

    printf("Enter the number of random numbers to generate: ");
    scanf("%d", &n);

    printf("Generated Random Numbers:\n");
    for(i = 0; i < n; i++) {
        printf("%d\n", rand());
    }

    printf("End of program.\n");

    return 0;
}
```
# OUTPUT:
![image](https://github.com/user-attachments/assets/a280ba00-a66d-4f2c-9899-bc2cde65d8f1)

# RESULT:
Hence, implementation of Pseudorandom Number Generation Using Standard library is implemented and executed successfully.
