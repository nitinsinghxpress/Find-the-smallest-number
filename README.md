# Find-the-smallest-number
//It is a c program to find the smallest number between given numbers.
# include<stdio.h>
int main(){
    int x, y, z;
    printf("enter the number : ");
    scanf("%d %d %d",&x,&y,&z);
    if(x <= y && x <= z){
        printf("smallest number in : %d",x);
    }
    else if(y <= x && y <= z){
        printf("smallest number is : % d",y);
    }

        else{
        printf("smallest number is : %d",z);
        }
        
    return 0;
}
