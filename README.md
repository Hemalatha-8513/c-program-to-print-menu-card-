# c-program-to-print-menu-card-
this is about printing menu card using swicth case
# include<stdio.h>
iny main( )
{
int a,qty,rate,total;
printf("\nMENU CARD \nselect your drink\n1.coffee \n2.tea \n3.cold coffee \n4.milk shake \n");
scanf("%d",&a);
switch(a)
{
case1:
printf("\n you have selected coffee.\n enter the quantity:");
scanf(" %d",&qty );
rate:5 ;
total= qty*rate;
printf("\n total amount:%d", total);
break;
case2:
printf("\n you have selected tea.\n enter the quantity:");
scanf("%d",&qty);
rate=10;
total=qty&rate;
printf9"\n total amount: total amount: %d",total);
break;
case3:
printf("\n you have selected cold coffee:\n enter the quantity:");
scanf("%d",&qty);
rate=15;
total=qty*rate;
printf("\n total amount : %d",total );
break;
case4:
printf("\n you have selected milk shake.\n enter the quantity:");
scanf("%d",&qty);
rate=20 
total=qty*rate  printf("\n total amount:%d", total);
break;
default:
printf ("\n sorry unavailable....%ds",a);
break;
}
return0;
}
