//# strcpy.c//
#include<stdio.h>
#include<string.h>
int main()
{
    char a[20],b[20];
    printf("Enter first styring:");
    scanf("%s",&a);
    printf("Enter second styring:");
    scanf("%s",&b);
    strcpy(a,b);
    puts(a);
    puts(b);
}
