# Comprehensive-Financial-Solution

**End-to-end financial management systems for businesses and individuals**(A collection of basic computational programs to solvereal-world problems using **C programming** . This project contains various calculations such as total cost, salaries, revenue, taxes, and other financial matrices.

## 1.Question number
This project addresses **Bachelor of science in applied information technology** class activity week-four(task five-basic calculations)

## 2.Description
The project aims to sove computational problems based on mathematical formulas provided in the task. This includes;
1. Total cost calculation,
2. Monthly salary calculation,
3. Net salary calculation,
4. Revenue generation,
5. Profit or loss percentage,
6. Discount amount,
7. Simple interest and compound interest,
8. VAT and break-even point, and more.

## 3.Installation steps
1. Navigate to the project repository
2. Compile the program using C compiler(e.g;GNU GCC)
3. Run the compiled program

## 4.Usage
_**example of usage**_
1. Calculate total cost
  >Input: Unit_price = 1500

  >Input: Quantity = 2000

  >total_cost = 3000000
2. Calculate monthly salary

  >Input: Hourly_wedge = 2500

  >Input: Hours_worked = 16000

  >monthly_salary = 40000000
Each program output result based on user-provided input or predefined constants

## 5.Features of the program
_**key features**_
1. Handles financial and mathematical calculations
2. Includes a wide range of scenarios;
  >Salary calculations,

  >Profit and loss analyses,

  >VAT and tax calculations,

3. Flexible input prompt for dynamic user input

## 6.Contributing
1. Create a repository
2. Create a new feature branch
3. Commit your changes
4. Push your branch
5. Open a pull request on github

## 7.License
This project is licensed under MIT license. see LICENSE file for details.

## 8.Auther and maintainer

_**Athour**_

Munduku Innocent

_**Maintainer**_

Munduku Innocent/Munduku coder

## 9.Acknologement

_**special thanks to**__

1. Dear mum, Angua Betty,
2. International Business Science and Technology University,
3. Fucality of information and communication technology,
4. Mr.Kato Kenneth, for providing the class activity task.
 #include <stdio.h>
#include <stdlib.h>

int main()
{
    //Question number one: Total Cost Calculation
    float unit_price, quantity, total_cost;
    printf("\nEnter the unit price of the item (UGX): ");
    scanf("%f", &unit_price);
    printf("\nEnter the quantity: ");
    scanf("%f", &quantity);
    total_cost = unit_price * quantity;
    printf("\nThe total cost is: UGX %.2f\n", total_cost);
    //Question number two: Monthly Salary Calculation
    float hourly_wage, hours_worked, monthly_salary;
    printf("\nEnter the hourly wage (UGX): ");
    scanf("%f", &hourly_wage);
    printf("\nEnter the number of hours worked in a month: ");
    scanf("%f", &hours_worked);
    monthly_salary = hourly_wage * hours_worked;
    printf("\nThe monthly salary is: UGX %.2f\n", monthly_salary);
    return 0;
    }











