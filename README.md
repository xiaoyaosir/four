#include<stdio.h>
int main()
{
int i,j,temp;
    for(i=1;i<numsSize;i++){
        temp=nums【i】;
        for(j=i;j>0&&temp<nums【j-1】;j--)
            nums【j】=nums【j-1】;
        nums【j】=temp;
    }
    return 0;
    }
