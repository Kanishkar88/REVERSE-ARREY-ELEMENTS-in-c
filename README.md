#include <stdio.h>
int main() {
    int arr[5];
    for(int i=1;i<5;i++){
        scanf("%d",&arr[i]);
    }
    for(int i=5-1;i>0;i--){
        printf("%d",arr[i]);
    }
    return 0;
}
