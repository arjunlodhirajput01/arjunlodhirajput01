- 👋 Hi, I’m @arjunlodhirajput01
- 👀 I’m interested in Programming 
- 🌱 I’m currently learning C Programming Launguage 

<!---
arjunlodhirajput01/arjunlodhirajput01 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


Chapter 2 

User-Defind Function

Question 1 

Ajay's basic salary is input through keyboard. His dearness allowanance is 40% of basic salary, 
and house rent allowanace is 20% of basic salary, Write a program to 
calculate his gross salary.

#include<stdio.h>
int main(){
    float basic_salary, allowanance, house_rent, gross_salary;
    printf("Enter the Basic Salary of Ajay :");
    scanf("%f", &basic_salary);
    
    allowanance = 0.4 * basic_salary;
    house_rent = 0.2 * basic_salary;
    
    gross_salary = basic_salary + allowanance + house_rent; 
    
    printf("The Basic Salary is %2.f \n", basic_salary);
    printf("Dearnance allowanance is %2.f \n", allowanance);
    printf("House rent is %2.f \n", house_rent);
    printf("Gross Salary  is %2.f \n", gross_salary);
    
    getc;
    return 0;
}
