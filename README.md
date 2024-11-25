5.Check character type (Alphabet, Digit and Special character )

Program

#include <stdio.h>
void main() 
{
printf("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~");
printf("\nProgram by : Dharshini S- I Year B.TECH. CSBS");
printf("\n~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~\n");


    char ch;
    printf("Enter a character: ");
    scanf("%c", &ch);
    if ((ch >= 'A' && ch <= 'Z') || (ch >= 'a' && ch <= 'z')) 
    {
        printf("The character '%c' is an alphabet\n", ch);
    }
    else if (ch >= '0' && ch <= '9') 
    {
        printf("The character '%c' is a digit\n", ch);
    }
    else
    {
        printf("The character '%c' is a special character\n", ch);
    }
} 

Output

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Program by : Dharshini S- I Year B.TECH. CSBS
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Enter a character : *
The character '*' is a special character

