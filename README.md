# Write-a-program-that-reads-a-positive-integer-and-displays-its-factorial
#include <stdio.h>

int main() {
    int n, i;
    unsigned long factorial = 1;
    printf("Enter a positive integer: ");
    scanf("%d", &n);
    if (n > 0) {
        for (i = 1; i <= n; ++i) {
            factorial *= i;
        }        printf("Factorial of %d = %lu\n", n, factorial);
    }
     else
        printf("Factorial of a negative number doesn't exist.\n");
    return 0;
}
