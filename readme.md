# 1.Prime number or not

```c
#include <stdio.h>
void main()
{
    int n,flag=0,i;
  //  printf("Enter n:");
    scanf("%d",&n);
    for (i=2;i<n;i++){
    if(n%i!=0){
    continue;
    }
    else {
        flag=1;
        printf("Not a prime");
        break;
        
    }
  }
  
     if(flag==0){
        printf("prime");
    
  }
    
}

```
