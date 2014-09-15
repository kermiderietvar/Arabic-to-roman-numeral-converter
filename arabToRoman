//
//  arabToRoman.c
//
//
//  Created by nimik on 15.09.14.
//  Copyright (c) 2014 nimik. All rights reserved.
//
#include <stdio.h>
#include <stdlib.h>

void arabtoroman(void);
int main(void)
{
    char entry;
    char konec;
    do
    {
        printf("\nSelect what do you want:\n");
        printf("1) Convert Arabic numerals to Roman numerals\n");
        printf("0) Exit the program\n");
        printf("Your selection: ");
        
        switch (entry = getchar())
        {
            case '1':
                while (1)
                {
                    konec = getchar();
                    if (konec == '\n')
                        break;
                }
               arabtoroman();
                break;
                        case '0':
                getchar();
                printf("Goodbye!\n");
                return 0;
                                    default:
                while (1)
                {
                    konec = getchar();
                    if (konec == '\n')
                        break;
                }
                printf("Invalid menu choice.  Please enter 1,or X.\n");
                system("sleep 1");
        }
    } while (entry != 'X');
    
    return 0;
}

//converts Arabic numerals to Roman numerals

void arabtoroman(void)
{
    int num;
    printf("Enter a positive integer no greater than 10000: ");
    scanf("%d", &num);
    printf("\n");
    
    if (num > 10000)
    {
        printf("E R R 0 R: number is too large!\n");
        getchar();
        system("sleep 0.2");
        return;
    }
    
    system("sleep 0.2");
    printf("Your number in Roman numerals is: ");
    
    while (num >= 1000)
    {
        printf("M");
        num -= 1000;
    }
    
    if (num >= 900)
    {
        printf("CM");
        num -= 900;
    }
    
    while (num >= 500)
    {
        printf("D");
        num -= 500;
    }
    
    if (num >= 400)
    {
        printf("CD");
        num -= 400;
    }
    
    while (num >= 100)
    {
        printf("C");
        num -= 100;
    }
    
    if (num >= 90)
    {
        printf("XC");
        num -= 90;
    }
    
    while (num >= 50)
    {
        printf("L");
        num -= 50;
    }
    
    if (num >= 40)
    {
        printf("XL");
        num -= 40;
    }
    
    while (num >= 10)
    {
        printf("X");
        num -= 10;
    }
    
    if (num >= 9)
    {
        printf("IX");
        num -= 9;
    }
    
    if (num >= 5)
    {
        printf("V");
        num -= 5;
    }
    
    if (num >= 4)
    {
        printf("IV");
        num -= 4;
    }
    
    while (num > 0)
    {
        printf("I");
        num -= 1;
    }
  
}


