# Find-the-max-of-3-numbers-a-b-c-entered-from-the-keyboard
Find the max of 3 numbers a,b,c entered from the keyboard
#include<stdio.h>
#include<conio.h>
main()
{
    int a,b,c,max;
    printf("Nhap a=");
    scanf("%d",&a);
    printf("Nhap b=");
    scanf("%d",&b);
    printf("Nhap c=");
    scanf("%d",&c);
    max=a; 
    if(b>max)
    {
          max=b; 
    }
    if(c>max)
      {
        max=c;
     }
    printf("gia tri lon nhat la: %d",max);
    getch();
}
