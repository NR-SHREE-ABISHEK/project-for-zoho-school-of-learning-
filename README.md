\\project-for-zoho-school-of-learning-
\\my first project for my zoho school of learning
#include <iostream>
using namespace std;
int main()
{
int m1, m2, m3, m4, m5;
int total;
float average;
char grade;
cout << "Enter 5 subject marks: ";
cin >> m1 >> m2 >> m3 >> m4 >> m5;
total = m1 + m2 + m3 + m4 + m5;
average = total/5;
if (average >= 90)
{
grade =A;
}
else if (average >= 80)
{
grade =B;
}
else if (average >= 70)
{
grade =C;
}
else if (average >= 60)
{
grade =D;
}
else 
{
grade =F;
}
cout << "\nTotal Marks = " << total;
cout << "\nAverage = " << average;
cout << "\nGrade = " << grade;
return 0;
}