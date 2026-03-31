# 25331A05E8-maximum-number
#include <stdio.h>

int main(){

    int a,b,c;
    printf("25331A05E8\n");

    printf("enter the numbers\n");
    scanf("%d%d%d",&a,&b,&c);
    if(a>b){
        if(a>c){
            printf("Greatest number is %d",a);
        }
        else{
        printf("Greatest number is %d",c);
    }
    }
    else{
        
        if(b>c){
        printf("Greatest number is %d",b);
    }
    else{
    printf("Greatest number is %d",c);
}
}
return 0;
}

