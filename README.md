# assignment-1
// C++ Bootcamp Assignment-1 Solved All Questions Here :-

1. Write A Program to Print  Hello Students On Screen :-
 code :-
#include<stdio.h>
int main()
{
    printf("hello students");
    getch();
    return 0;
}

Q2.  Write a program to print Hello in the first line and Students in the second line.

 code:-
 #include<stdio.h>
int main()
{
    printf("hello\nstudents");
    getch();
    return 0;
}

Q3 . Write a program to print “MySirG” on the screen. (Remember to print in double quotes)
   
   code:-
     #include<stdio.h>
int main()
{
    printf("\"MySirG\"");
    getch();
    return 0;
}


Q4. WAP to find the area of the circle. Take radius of circle from user as input and print the
result in below given format.

  code:-
     #include<stdio.h>
int main()
{
    float radius,area;
     printf("Enter Radius of Circle:");
     scanf("%f",&radius);
     area = 3.14 * radius * radius ;
     printf("\"Area of Circle is %.3f having the Radius %.3f\"",area,radius);
    getch();
    return 0;
}


Q5 WAP to calculate the length of String using printf function.
 code:-
 #include<stdio.h>
int main()
{
    int length;
     length = printf("My name is utsav gupta \n");
     printf("Length of String is :%d", length);

    getch();
    return 0;
}

Q6. WAP to print the name of the user in double quotes.
  code:-
    #include<stdio.h>
int main()
{
    printf("\"Hello, Aditiya sir\"");

    getch();
    return 0;
}

Q7.WAP to print “%d” on the screen.
code:-
#include<stdio.h>
int main()
{
     printf("%%d");
    getch();
    return 0;
}

Q8. WAP to print “\n” on the screen.
#include<stdio.h>
int main()
{
     printf("\\n");

    getch();
    return 0;
}

Q9. WAP to print “\\” on the screen.
#include<stdio.h>
int main()
{
     printf("\\\\");


    getch();
    return 0;
}

Q10. WAP to take date as an input in below given format and convert the date format and
display the result as given below.
#include<stdio.h>
int main()
{
     int date,month,year;
     printf("Enter Date in this Format:- DD/MM/YYYY\n");
     scanf("%d/%d/%d",&date,&month,&year);
     printf("Converted Date :-\n");
     printf("Day - %d , Month - %d , Year - %d",date,month,year);



    getch();
    return 0;
}
Q11.  WAP to take time as an input in below given format and convert the time format and
display the result as given below.
 code:-
 #include<stdio.h>
int main()
{
     int hour,minute;
     printf("Enter Time in this Format:- HH:MM\n");
     scanf("%d:%d",&hour,&minute);
     printf("Converted Time :-\n");
     printf("%d Hour and %d  Minutes",hour,minute);


    getch();
    return 0;
}

 Q12. Find output of below code:
int main()
{
int x = printf(“ineuron”);
printf(“%d”,x);
return 0;
}
  sol:- 
    Output of Above Code is :ineuron7
