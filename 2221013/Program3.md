### Program 3: Input Username and Roll number using Scanf

```c
#include<stdio.h>

int main(){

int Roll_No;
char Username[50];

printf(" What is your Username ?  ");
scanf("%s", Username);
printf(" What is your Roll No ? ");
scanf(" %d", &Roll_No);
printf("\n Your Username is ");
printf("%s", Username);
printf("\n Your Roll no is ");
printf("%d \n", Roll_No);

return 0;
}
```
**Output: What is your Username ? Amrinder**

**What is your roll no ? 2221013**

**Your Username is Amrinder**

**Your Roll no is 2221013**
