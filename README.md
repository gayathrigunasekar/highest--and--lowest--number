# highest--and--lowest--number
highest and lowest number in array using c
#include<studio.h>
int main()
{
int i,max,min,size;
printf("enter size of array");
scanf("%d",&size);
printf("enter elements in array:");
for(i=0;i<size;i++)
{
scant("%d",&arr[i]);
}
max=arr[0];
min=arr[0];
for(i=1;i<size;i++)
{
if(arr[i]>max)
{max=arr[i];
}
}
if(arr[i]<min)
{
min=arr[i];
}
printf("maximum element=%d\n",max);
printf("minimum element=%d\n",min);
return 0;
}
