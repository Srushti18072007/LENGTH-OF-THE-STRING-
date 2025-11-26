#include <stdio.h>

int stringLength(char str[]) {
    int i = 0;
    while (str[i] != '\0') {  
        i++;
    }
    return i;
}

int main() {
    char str[100];

    printf("Enter a string: ");
    scanf("%s", str);  
    int len = stringLength(str);

    printf("\nLength of the string is: %d\n", len);
    printf("====================================");

    return 0;
}

