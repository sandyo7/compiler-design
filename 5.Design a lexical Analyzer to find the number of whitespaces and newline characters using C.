#include <stdio.h>
int main()
{
    char str[100];//input string with size 100

    int words=0,newline=0,characters=0; // counter variables

    scanf("%[^~]",&str);//scanf formatting    

    for(int i=0;str[i]!='\0';i++)
     { 
         if(str[i] == ' ')
         { 
              words++;
         }
         else if(str[i] == '\n')
         {
             newline++;
              words++;//since with every next line new words start. corner case 1
         }
         else if(str[i] != ' ' && str[i] != '\n'){
         characters++;
         }
     }
    if(characters > 0)//Corner case 2,3.
    {
        words++;
        newline++;
    }
     printf("Total number of words : %d\n",words);
     printf("Total number of lines : %d\n",newline);
     printf("Total number of characters : %d\n",characters);
    return 0;
}

Output:
void main()
{
int a;
int b;
a = b + c;
c = d * e;
}
Total number of words : 18
Total number of lines : 7

Exp. No. 6                            
Develop a lexical Analyzer to test whether a given identifier is valid or not using C.

Program:
#include<stdio.h> 
#include<conio.h> 
#include<ctype.h>
int main()
{
	char a[10]; 
	int flag, i=1; 
	printf("\n Enter an identifier:"); 
	gets(a);
	if(isalpha(a[0]))
		flag=1; 
	else
		printf("\n Not a valid identifier");
		while(a[i]!='\0')
	{
		if(!isdigit(a[i])&&!isalpha(a[i]))
		{
			flag=0; 
			break;
		} i++;
	}
	if(flag==1)
		printf("\n Valid identifier"); 
}
