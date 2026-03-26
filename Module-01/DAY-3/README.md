# Ex.No:1(C) CONTROL STATEMENTS

## AIM:
To develop a Java program to check given number is zero or not.

## ALGORITHM :
1.	 Start the program.
2.	Import the Scanner class to read input from the user.
3.	Define a class named Demo.
4.	Inside the class, define a method check(int num) that:
5.	Calculates the square of the number.
6.	Prints the squared result.
7.	In the main() method:
8.	Create a Scanner object to take input.
9.	Read an integer input and store it in the variable num.
10.	Create an object s of the Demo class.
11.	Call the check(num) method using the object s.
12.	End the program.




## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: Yuvan M
RegisterNumber:  212223240188
*/
```

## Sourcecode.java:

```
import java.util.Scanner;
public class Demo {
public void check(int num){
    num=num*num;
    System.out.println(num);
}
public static void main(String[] args) 
    {
        Scanner in = new Scanner(System.in);
        int num=in.nextInt();
    Demo s=new Demo();
    s.check(num);   
    }
}

```







## OUTPUT:


<img width="611" height="171" alt="image" src="https://github.com/user-attachments/assets/cb551b07-404f-44d9-98b8-115f9d0d55b0" />






## RESULT:
Thus, the Java program to check given number is zero or not was created successfully.

