# work
#include <stdio.h>
#include <stdlib.h>

int main()
{
int n, max, min;
int i;
for (i=0; i<n; i++)
    scanf("%d", &n);
max=0; min=0;
for (i=0; i<n; i++)
    {if (i>max) max=i;}
for (i=0; i<n; i++)
   {    if (i<min) min=i;}
printf("max=%d\n", max);
printf("min=%d", min);
}
This is a mistake
end
