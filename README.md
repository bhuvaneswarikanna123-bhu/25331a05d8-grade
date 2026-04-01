# 25331a05d8-grade
#include <stdio.h>
int main() {
int marks;
printf("enter your marks\n");
scanf("%d",&marks);
if(marks>=90) {
printf("your grade is a\n");
}
else if (marks>=75) {
printf("your grade is b\n");
}
else if(marks>=60) {
printf("your grade is c\n");
}
else{
printf("you failed\n");
}
return 0;
}
