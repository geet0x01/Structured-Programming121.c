# Structured-Programming121.c
#include <stdio.h>
int main() {
    int a, b, option, summation, subtraction, multiplication;
    float division;
    printf("Enter the first number:");
    scanf("%d", &a);
    printf("Enter the second number:");
    scanf("%d", &b);
    printf("1.Summation\n2.Subtraction\n3.Multiplication\n4.Division\nEnter any option(1 to 4):");
    scanf("%d", &option);
    switch(option)
    {
        case 1:
        summation = a + b;
        printf("Sum:%d\n", summation);
        break;
        case 2:
        subtraction = a - b;
        printf("Subtraction:%d\n", subtraction);
        break;
        case 3:
        multiplication = a * b;
        printf("Multiplication:%d\n", multiplication);
        break;
        case 4:
        division = (float)a / b;
        printf("Division:%.2f\n", division);
        break;
        default:
        printf("Enter valid option");
    }
    return 0;
}
