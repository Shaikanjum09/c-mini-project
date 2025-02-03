//PETROL MANAGMENT SYSTEM
#include <stdio.h>
int main() {
    int choice;
    int qn;
    printf("\t petrol mangement system\n");
    printf("refill the petrol\n");
    printf("refill the diesel\n");
    printf("refill the cng\n");
    printf("service the vehicle\n");
    printf("enter your choice:");
    scanf("%d",&choice);
    switch(choice){
        case 1:printf("refill the petrol");
               printf("quantity ");
               scanf("%d",&qn);
               printf("amount:%d",qn*70);
               break;
        case 2:printf("refill the diesel");
               printf("quantity ");
               scanf("%d",&qn);
               printf("amount:%d",qn*90);
               break;
        case 3:printf("refill the cng");
               printf("quantity ");
               scanf("%d",&qn);
               printf("amount:%d",qn*60);
               break;
        case 4:printf("service vehicle");
              // printf("quantity ");
               //scanf("%d",&qn);
               printf("service amount:%d",30);
               break;
        default:printf("none of above");
               break;
    }
    return 0;
}
