#include <stdio.h>
#include <stdlib.h>

int main(int argc, char *argv[]) {
    if (argc != 4) {
        printf("Usage: %s [operator] [num1] [num2]\n", argv[0]);
        return 1;
    }

    char operator = argv[1][0];
    double num1 = atof(argv[2]);
    double num2 = atof(argv[3]);
    double result;

    switch (operator) {
        case '+':
            result = num1 + num2;
            break;
        case '-':
            result = num1 - num2;
            break;
        case '*':
            result = num1 * num2;
            break;
        case '/':
            if (num2 == 0) {
                printf("Error: Division by zero.\n");
                return 1;
            }
            result = num1 / num2;
            break;
        default:
            printf("Invalid operator. Use +, -, *, or /\n");
            return 1;
    }

    printf("Result: %.2lf\n", result);
    return 0;
}



output: 


C:\Users\FARDHOSA>cd documents

C:\Users\FARDHOSA\Documents>calculator + 2 2
Result: 4.00

C:\Users\FARDHOSA\Documents>calculator * 2 2
Result: 4.00

C:\Users\FARDHOSA\Documents>calculator * 2 8
Result: 16.00
