// #include<stdio.h>
// int main () {

//     float principalamount, interestrate, time, simpleintreste;

//     printf("Enter a principle amount is :");
//     scanf("%f",&principalamount);

//      printf("Enter a interest rate is :");
//     scanf("%f",&interestrate);
//     interestrate= interestrate/100;

//      printf("Enter a time in years is :");
//     scanf("%f",&time);

//     simpleintreste = principalamount*interestrate*time;

//     printf("simple intrest is %.2f\n",simpleintreste); 


// }

// #include <stdio.h>

// int main() {
//     int num;
//     char *result[2] = {"Even", "Odd"};
    
//     printf("Enter a number: ");
//     scanf("%d", &num);
    
//     printf("%d is an %s number.\n", num, result[num % 2]);
    
//     return 0;
// }

// #include<stdio.h>
// int main () {
//     int num1, num2;

//     printf("enter a number");
//     scanf("%d %d",&num1,&num2);

//     num1%2==0 && printf("%d is a even number \n",num1) || printf("%d is a odd number",num1); 
//     num2%2==0 && printf("%d is a even number\n",num2) || printf("%d is a odd number",num2); 
   
// }

// #include<stdio.h>
// int main () {
//     float totalbill;
//     int people , amount;

//     printf("Enter a total bill amount\n");
//     scanf("%f", &totalbill);

//     printf("Enter a number of people");
//     scanf("%d", &people);

//     amount = totalbill/people;

//     printf("%d \n amount of each person needs to pay \n",amount);

//     return 0;

// }

// #include<stdio.h>
// int main () {
//     float radius , volume;


//     printf("Welcome to Sphere Volume Calculator!:\n");
//     printf("Enter a radius of sphare:");
//     scanf("%f",&radius);

//     volume= (4.0/3.0)*3.14* radius*radius*radius;

//     printf("volume of sphare is : %.2f",volume);


// }

// #include<stdio.h>
// int main () {
//     int quantity,price; 
//     float totalcost;

//     printf("Enter the quantity you want to purchase:\n");
//     scanf("%d",&quantity);

//     printf("%d\n",quantity);


//     printf("Enter the price of Chocolate Cake:Rs.\n");
//     scanf("%d",&price);

//     printf("%d\n",price);

//     totalcost = quantity*price;

//     printf("total cost :Rs. %f\n",totalcost);

//     return 0;

// }

// #include<stdio.h>

// int main() {
//     int a, b;

//     printf("Enetr a number:\n");
//     scanf("%d %d",&a, &b);

    
//     printf("a & b= %d\n",a & b);
//     printf("a | b=%d\n",a | b);
//     printf("a ^ b=%d\n",a ^ b);
//     printf("~a = %lu\n",~a);
//     printf("a <<1 = %d\n",a<<1);
//     printf(" a >> 1 =%d\n",a>>1);

//     return 0;
// }

// #include <stdio.h>

// int main() {
//     int num1, num2;
//     char operator;

    
//     printf("Enter 1st number: ");
//     scanf("%d", &num1);
//     printf("Enter 2nd number: ");
//     scanf("%d", &num2);
//     printf("Enter operator (+,-,*,/): ");
//     scanf(" %c", &operator);

    
//     switch (operator) {
//         case '+':
//             printf("addition = %d\n", num1 + num2);
//             break;
//         case '-':
//             printf("subtraction = %d\n", num1 - num2);
//             break;
//         case '*':
//             printf("multiplication = %d\n", num1 * num2);
//             break;
//         case '/':
//             if (num2 != 0) {
//                 printf("division = %d\n", num1 / num2);
//             } else {
//                 printf("Error: Division by zero is not allowed.\n");
//             }
//             break;
//         default:
//             printf("Error: Invalid operator.\n");
//     }

//     return 0;
// }


// #include <stdio.h>

// int main() {
//     int num1, num2;
//     char operator;

//     printf("Enter 1st number: ");
//     scanf("%d", &num1);
//     printf("Enter 2nd number: ");
//     scanf("%d", &num2);
//     printf("Enter operator (+,-,*,/): ");
//     scanf(" %c", &operator);

    
//     int addition = (operator == '+') && printf("addition = %d\n", num1 + num2);
//     int subtraction = (operator == '-') && printf("subtraction = %d\n", num1 - num2);
//     int multiplication = (operator == '*') && printf("multiplication = %d\n", num1 * num2);
//     int division = (operator == '/') && (num2 != 0) && printf("division = %d\n", num1 / num2);
//     int division_error = (operator == '/') && (num2 == 0) && printf("Error: Division by zero is not allowed.\n");
//     int invalid_operator = !(operator == '+' || operator == '-' || operator == '*' || operator == '/') && printf("Error: Invalid operator.\n");

//     return 0;
// }


// #include<stdio.h>
// int main () {
//     int x , y;

//     printf("Enter a two number x,y :\n");
//     scanf("%d %d",&x,&y);

//     printf("x==y = %d\n",x==y);
//     printf("x!=y = %d\n",x!=y);
//     printf("x>y = %d\n",x>y);
//     printf("x<y = %d\n",x<y);
//     printf("x>=y = %d\n",x>=y);
//     printf("x=<y = %d\n",x<=y);
    
//     return 0;
// }

// #include<stdio.h>
// int main () {

//     int a, b;

//     printf("Enter a two number a and b :\n");
//     scanf("%d %d ",&a,&b);

//     printf("a+= :%d\n",a+=b);
//     printf("a-= :%d\n",a-=b);
//     printf("a*= :%d\n",a*=b);
//     printf("a/= :%d\n",a/=b);
//     printf("a%= :%d\n",a%=b);

//     return 0;
// }

// #include<stdio.h>

// int main(){
//     char name[30];    
//     char department[50];
//     int empId;
//     float salary;

//     printf("Enter employee name: ");
//     scanf("%s", name);  

//     printf("Enter employee ID: ");
//     scanf("%d", &empId);

//     printf("Enter employee designation: ");
//     scanf("%s", department); 
//     printf("Enter employee salary: ");
//     scanf("%f", &salary);

//     printf("Employee Details\n");
//     printf("Name: %s\n", name);
//     printf("Employee ID: %d\n", empId);
//     printf("Designation: %s\n", department);
//     printf("Salary: $%.2f\n", salary);

//     return 0;
// }
