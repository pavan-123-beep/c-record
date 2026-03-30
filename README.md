#include<stdio.h>
#include<string.h>
	int main(){
	char str1[100],str2[100];
	char copystr[100];
	printf("enter the string 1\n");
	scanf("%s",&str1);
	printf("enter the string 2\n");
	scanf("%s",&str2);
	printf("length of string 1:%lu\n",strlen(str1));
	printf("length of string 2:%lu\n",strlen(str2));
	strcpy(copystr,str1);
	printf("\n copied string:%s",copystr);
	strcat(str1,str2);
	printf("\n concatinated string:%S",str1,str2);
	if (strcmp(copystr,str2)==0)
	printf("\nstrings are equal");
	else
	printf("\n strings are not equal");
	return 0;
	}
