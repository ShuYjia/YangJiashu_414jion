# YangJiashu’s Repository
## My Introduction
  Hellow,my name is YangJiashu,which come for Chendu,Sichuan.I have a good command of paper folding.I love use some application such as Photoshop and Adobe Illustrator,to improve some defective photos and create posters.I learned visual studio in high school.Of course,I like playing games on phone,which can relax myself.
 ## The reasons of Join 414 Laboratory
  I want to learn some kowledge about writing codes and the method of use Unity and UE to create my games.    
  I want get some resource of professional equipment and more chance to create some splendid works with classmates.
  ![image name](https://sukiui.com/i/2022/09/20/3x03g.jpg)
# Bubble Sort
Begin  
#include<stdio.h>  
int main()  
{  
    int a[7] = { 38,12,42,120,98,67,3 };//input the number of items you want to compare and the items you want to compare   
    int i = 0;                              //set the first number   
    int j = 0;                              //the substitution of element's number   
    int k;                                  // a variate will be used in change of position   
    for (i; i < 6; i++)               //set the conditon of circulation that ensure the maximum number is the last one   
    {   
        for (j; j < 6 - i; j++)     //set the  circulation of exchange   
        {    
            if (a[j] > a[j + 1])      // the condition of exchange    
            {   
                k = a[j];   
                a[j] = a[j + 1];   
                a[j + 1] = k;   
            }   
        }   
    }   
    for (i = 0; i < 7; i++)   
    {   
        printf("%d\x20", a[i]);   
    }     
}   
End  
