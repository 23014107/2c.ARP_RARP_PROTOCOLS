# EXP NO:1                                                                      DATE: 5-2-24
#                        Find the ASCII character of the given value.
# AIM:
To Write a C PROGRAM to find the ASCII character of the given value.

# ALGORITHM:
1.Start
2. Declare integer variable n.
3. Read integer input into n using scanf.
4.Print character corresponding to ASCII value of n using printf.
5.End

# PROGRAM:
#include <stdio.h>
int main()
{
int n;
scanf("%d",&n);
printf("Character of ASCII Value %d is %c",n,n);
return 0;
}
# OUTPUT:

# RESULT:
Thus,the ASCII value is executed successfully.

# EXP NO:2                                                             DATE:5-2-24
#                    Find sum of three numbers
# AIM: 
To Write a PROGRAM to find sum of three numbers.
# ALGORITHM:
1.Start
2. Declare integer variables n1, n2, n3, and sum.
3.Read three integer inputs into n1, n2, and n3 using scanf.
4. Calculate the sum of n1, n2, and n3 and store it in sum.
5. Print the sum using printf.
6.End
# PROGRAM:
#include <stdio.h>
int main()
{
int n1,n2,n3,sum;
scanf("%d %d %d",&n1,&n2,&n3);
sum=n1+n2+n3;
printf("Sum is:%d",sum);
return 0;
}
# OUTPUT:

# RESULT:
Thus,the sum of three numbers is executed successfully


# EXP NO : 3                                               DATE:6-2-24

#             C PROGRAM to check whether the grade is A grade
# AIM:
To Write a C PROGRAM to check whether the grade is A grade using simple if statement.
# ALGORITHM:
1.Start.
2. Declare a character variable a.
3. Read a character input into a using scanf.
4. Check if the value of a is equal to 'A' using an if statement.
5. If a is equal to 'A', print the message "Grade is A" using printf.
6.End.

# PROGRAM:

#include<stdio.h>
int main()
{
char a;
scanf("%c",&a);
if(a=='A');
printf(" Grade is %c",a);
return 0;
}

# OUTPUT:

# RESULT:
Thus,grade is executed successfully


# EXP NO:4                                                                  DATE:6-2-24
#                     C PROGRAM to read N value and check that value is equal to 10 or not
# AIM:
To Write a C PROGRAM to read N value and check that value is equal to 10 or not using if-else.

# ALGORITHM:
1.Start
2.Declare an integer variable ‘N’
3.Read an integer input into ‘N’ using ‘scanf’
4.Check if the value of N is equal to 10 using an if statement.
5. If N is equal to 10, print the message "Given number is TEN." using printf.
6. If N is not equal to 10, print the message "Given number is NOT TEN." using printf.
7.End

# PROGRAM:
#include<stdio.h>
int main()
{
int N;
scanf("%d",&N);
if(N==10)
printf("Given number is TEN.");
else
printf("Given number is NOT TEN.");
return 0;
}

# OUTPUT:


# RESULT:

Thus,the required PROGRAM is written and executed successfully.


# EXP NO:5                                               DATE:7-2-24
#                Find principle amount
# AIM:
To Write a C PROGRAM to find principle amount based on compound interest, time & rate of interest.
# ALGORITHM:
1.Start
2. Declare variables: principal amount (P), time in years (t), rate of interest per annum (r), and
compound interest (CI).
3. Read P, t, and r from the user.
4.Calculate rate using this formula,rate=rate/100
5.calculate principle using this formula, principle=compound/(pow(1+rate,time))
6. Print the calculated principal amount.
7.End
# PROGRAM:
#include <stdio.h>
#include<math.h>
int main()
{
float principle,rate,time,compound;
scanf("%f",&compound);
scanf("%f",&time);
scanf("%f",&rate);
rate=rate/100;
principle=compound/(pow(1+rate,time));
printf("Principle Amount is = %.2f",principle);
return 0;
}
# OUTPUT:

# RESULT:
Thus,the principle amount is written and executed successfully.

