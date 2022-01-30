# quiz-game-c-language
#include<stdio.h>    
int main()
{
     int a;
     char name; //for player name
     printf(" \n \t\t\t QUIZ GAME \n");
     printf(" \nENTER YOUR NAME   ");
     scanf("%s",&name);
     printf("\n\t\t\t PLAYER NAME IS %s",&name);
     printf("\n\n\t\t\t [ SELECT AND ENTER THE ANSWER NO. ]");
     printf("\n\n\t\t Q1.WHAT IS THE CAPITAL OF THE INDIA ?\n");
     printf(" \n\n\n\t\t 1. DELHI \n\t\t 2. MUMBAI\n\t\t 3. CHENNAI\n\n\t");
     scanf("%d",&a);
       if (a==1)         // winning condition
            printf(" \n\n\t\t CORRECT !!!");
       else          // for invalid input
            printf("\n\t\t WRONG !!! ");
     printf("\n\n\t\t Q1.WHAT IS THE NATIONAL ANIMAL OF THE INDIA ?\n");
     printf(" \n\n\n\t\t 1. PEACOCK \n\t\t 2. TIGER\n\t\t 3. MONKEY\n\n\t");
     scanf("%d",&a);
       if (a==2)         // winning condition
            printf(" \n\n\t\t CORRECT !!!");
       else          // for invalid input
            printf("\n\t\t WRONG !!! ");
     printf("\n\n\t\t Q1.WHAT IS THE CAPITAL OF TAMIL NADU ?\n");
     printf(" \n\n\n\t\t 1. MADURAI\n\t\t 2. NAMAKKAL\n\t\t 3. CHENNAI\n\n\t");
     scanf("%d",&a);
       if (a==3)         // winning condition
            printf(" \n\n\t\t CORRECT !!!");
       else          // for invalid input
            printf("\n\t\t WRONG !!! ");
    
 return 0; 
  }
