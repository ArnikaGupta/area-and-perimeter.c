#include <stdio.h>

int main() {
    int l,b;
    printf("Enter the length and breadth:");
    scanf("%d%d",&l ,&b);
    printf("the area of rectangle is:%d \n",l*b);
    printf("The perimeter of rectangle is:%d",2*(l+b));
    return 0;
}
