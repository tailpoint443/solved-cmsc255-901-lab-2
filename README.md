Download Link: https://assignmentchef.com/product/solved-cmsc255-901-lab-2
<br>
Big Java, Late Objects / Java for Everyone, 2e

Chapter Number: 2 Fundamental Data Types

1) Write a program that does the following: Create seven variables, one for each of the primitive number types in Java, and initialize each variable with any appropriate value. Print out the name of each variable and its value. Modify the value of each variable with an assignment statement and print out the names of the variables and their new values.




Next, create seven constants, one for each of the primitive number types in Java. Print the name of the constant and its value.




What happens if you try to assign a value to a constant?







2) Execute the program below. Each invocation of println outputs an arithmetic expression. The first two println commands are followed by comments that describe the operations that occur in each expression. Complete the program by adding a comment after each println statement that describes all the arithmetic operations that occur when evaluating the expression that is printed.

public class Expressions{   public static void main(String[] args)   {      int a = 3;       int b = 4;      int c = 5;      int d = 17;      System.out.println((a + b)/ c);      // 3 and 4 are added with sum 7      // 7 is divided by 5 with quotient 1      System.out.println(a + b / c);      // 4 is divided by 5 with quotient 0      // 3 is added to 0 with sum 3      System.out.println(a++);      System.out.println(a–);      System.out.println(a + 1);       System.out.println(d % c);      System.out.println(d / c);      System.out.println(d % b);      System.out.println(d / b);      System.out.println(d + a / d + b);      System.out.println((d + a) / (d + b));      System.out.println(Math.sqrt(b));      System.out.println(Math.pow(a, b));      System.out.println(Math.abs(-a));      System.out.println(Math.max(a, b));   }}







3) Write a program that prompts the user to enter two integers. Print the smaller of the two numbers entered. You’ll need to use a Scanner and a Math method.







4) Suppose you have 5 1/2 gallons of milk and want to store them in milk jars that can hold up to 0.75 gallons each. You want to know ahead of time how many completely filled jars you will have. The following program has been written for that purpose.




What is wrong with it?




Why?




How can you fix it?


