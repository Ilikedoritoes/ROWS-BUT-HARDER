
#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>
#include <stdlib.h>

    void main()
    { 
     
        int colume = 1, line = 1, rows, space;
        int ro = 0;
        printf("how many rows do you want?\n");
        scanf("%d", &rows);
        
        ro = rows / 2;
        space = ro;
        while (rows <= 0)
        {
            printf("WRONG WRONG!!");
        }
        printf("ok\n");
        
        printf("*\n");

        for (line = 1; line <= rows; line++)
        {
               for (colume = 1; colume <= line; colume++)
               {

                   while (space <= ro)
                   {
                       printf("_");
                       space--;
                   }

               printf("**");
               }
        printf("\n");
        }
        system("pause");
    }
