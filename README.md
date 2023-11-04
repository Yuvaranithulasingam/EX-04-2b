# EX-4(B)     DISPLAY THE GRADES USING SIMPLE IF-ELSE STATEMENT

## AIM:
To write a C program to display the remarks for the grade using simple if statement

## ALGORITHM:
1: Start the program.

2: Read a character (c) from the user.

3: Check the value of c using conditional statements:

a) If c is equal to 'A', print "Excellent!!".
b) If c is equal to 'B', print "Good!!".
c) If none of the conditions above are met, the program will end without printing anything.

Step 4: Stop the program.

## PROGRAM:
```
#include <stdio.h>
int main()
{
   char c;
   scanf("%c",&c);
   if(c=='A')
   {
      printf("Excellent!!");
   }
   else if(c=='B')
   {
      printf("Good!!");
   }
}
```

## OUTPUt:
![image](https://github.com/Yuvaranithulasingam/EX-04-2b/assets/121418522/0283b054-d785-468c-8631-f34008b0c648)

## RESULT:
Thus, the program is successfully verified.
