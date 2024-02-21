#include <stdio.h>

int main() {
    int marks;

    // Input marks
    printf("Enter the marks obtained: ");
    scanf("%d", &marks);

    // Check the class based on marks
    if (marks >= 80 && marks <= 100) {
        printf("Class: Distinction\n");
    } else if (marks >= 60 && marks < 80) {
        printf("Class: First Division\n");
    } else if (marks >= 50 && marks < 60) {
        printf("Class: Second Division\n");
    } else if (marks >= 40 && marks < 50) {
        printf("Class: Third Division\n");
    } else if (marks >= 0 && marks < 40) {
        printf("Class: Fail\n");
    } else {
        printf("Invalid marks!\n");
    }

    return 0;
}
