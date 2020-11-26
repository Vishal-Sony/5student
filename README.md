# 5student
#include<stdio.h>
int main()
{
    int marks[5];
    char name[5][20];
    char UID[5][10];
    int i,j,n;
    printf("Enter the number of students whose data you want to store :");
    scanf("%d",&n);
    for(i=0;i<n;i++)
    {
        printf("\nEnter details of the student :\n");
        printf("Enter Name :");
        scanf("%s",name[i]);
        printf("\nEnter UID :");
        scanf("%s",UID[i]);
        printf("\nEnter total marks :");
        scanf("%d",&marks[i]);
    }
    printf("The data stored in the system are : \n");
    for(i=0;i<n;i++)
    {
        printf("Name :- %s\n",name[i]);
        printf("UID :- %s\n",UID[i]);
        printf("Marks :-%d\n",marks[i]);
    }
    return 0;

}
