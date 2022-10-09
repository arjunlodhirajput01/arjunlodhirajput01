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

Q2. The distance between two cities (in km.) is input through the keyboard.
wrtie a program to convert and print this distance in meters, feets, inches and centimenters.

#include<stdio.h>
int main(){
    float Kilometers, Meters, Feets, Inches, Centimeters;
    printf("Enter the Distance is Kilometers :");
    scanf("%f", &Kilometers);
    
    Meters = Kilometers * 1000;
    Feets = Kilometers *  3280.84 * 100;
    Inches = Kilometers * 39370.1;
    Centimeters  =  Kilometers * 100000;
    
    printf("The Distance in Meters is : %f \n", Meters);
    printf("The Distance in Feets is : %f \n", Feets);
    printf("The Distance in Inches is : %f \n", Inches);
    printf("The Distance in Centimeters is : %f \n", Centimeters);
    return 0;
}

Output 

Enter the Distance is Kilometers :2
The Distance in Meters is : 2000.000000 
The Distance in Feets is : 656168.000000 
The Distance in Inches is : 78740.203125 
The Distance in Centimeters is : 200000.000000 

Q3. The marks obtained by a student in five different subjects are input thorugh the keyboard, find out the aggregate marks and percentage marks obtained by the student. Assume that the maximum marks that can be obtained by a student in each subject is 100.

#include<stdio.h>
int main(){
    float total, english, hindi, maths, science, arts, percentage;
    
    printf("Enter the English Marks of Student :");
    scanf("%d", &english);
    printf("Enter the Hindi Marks of Student :");
    scanf("%d", &hindi);
    printf("Enter the Maths Marks of Student :");
    scanf("%d", &maths);
    printf("Enter the Science Marks of Student :");
    scanf("%d", &science);
    printf("Enter the Marks of Arts :");
    scanf("%d", &arts);
    
    total = hindi + english + maths + science + arts;
    percentage = total / 5;
    
    printf("The total marks of Student is: %d \n", total);
    printf("Student Percentage is: %0.2f \n", percentage);
    return 0;
}

Output

Enter the English Marks of Student :50
5Enter the Hindi Marks of Student :50
Enter the Maths Marks of Student :50
Enter the Science Marks of Student :50
Enter the Marks of Arts :60
The total marks of Student is: 260.000000 
Student Percentage is: 52.00 

Q4. Temperature of a city in fahrenheit degree is input through the keyboard. Write a program to convert this temperature into centigrade degree.

#include<stdio.h>

int main()
{
    float f, c;
    printf("Enter Temperature in Fahrenheit: ");
    scanf("%f", &f);

    c = (f-32)*5/9;

    printf("The Temperature in Centigrade Degree: %.2f", c);
    return (0);
}

Output

Enter Temperature in Fahrenheit: 98
The Temperature in Centigrade Degree: 36.67
 
Q5. The length & breath of a rectangle and radius of circle are input through the keyboard. Write a program to caluclate the area & perimeter of the rectangle, and the area & circumference of the circle.

#include<stdio.h>
int main()
{
    float l, b, r,ca, cc, ra, rp;

    //For rectangle
    printf("Enter the length of rectangle: ");
    scanf("%f", &l);
    printf("Enter the breadth of rectangle: ");
    scanf("%f", &b);

    //For circle
    printf("Enter the radius of circle: ");
    scanf("%f", &r);

    //Calculate area & perimeter of the rectangle...
     ra = l * b;    //Area of Rectangle = Length x Breadth
     rp = 2 * (l + b);    //Perimeter of Rectangle = 2 x (Length + Breadth) or addition of all sides

     //Calculate are & circumference of the circle...
     ca = 3.14 * r * r;   //Area of Circle = 2 x Pi x r^2 where Pi = 3.14
     cc = 2 * 3.14 * r;  //Circumference of Circle = 2 x Pi x r

     printf("\nThe area of the rectangle: %0.2f", ra);
     printf("\nThe perimeter of the rectangle: %.2f", rp);
     printf("\n\nThe area of the circle: %.2f", ca);
     printf("\nThe circumference of the circle: %.2f", cc);

     return (0);
}

Output 

Enter the length of rectangle: 3
Enter the breadth of rectangle: 2
Enter the radius of circle: 2
The area of the rectangle: 6.00
The perimeter of the rectangle: 10.00

The area of the circle: 12.56
The circumference of the circle: 12.56

