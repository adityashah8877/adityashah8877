//CONCATENATE OR APPEND TWO STRINGS IN C
#include<stdio.h>
#include<string.h>
int main(){
    char name[1000];
   char name2[2000];
   int l1,l2;
   gets(name);
   gets(name2);
   puts(name);
   puts(name2);
   l1=strlen(name);
   l2=strlen(name2);

    strncat(name,name2,l1+l2); 
    puts(name);
    }
