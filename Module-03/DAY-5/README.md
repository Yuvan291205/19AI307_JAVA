# Ex.No:3(E)  STRINGBUILDER OBJECT REFERENCE IN JAVA

## AIM:
To write a Java program that creates a StringBuilder object using a given string and assigns its reference to the variable sb.

## ALGORITHM :
Step 1: Start

Step 2: Import the required classes:
import java.util.* for Scanner and StringTokenizer.

Step 3: Create the Main class.

Step 4: Inside the main method:

a. Create a Scanner object to read user input.

b. Read a full line of text input from the user using nextLine().

c. Create a StringTokenizer object with the input string as its argument.

d. Use countTokens() method to count the number of tokens (words separated by whitespace by default).

e. Print the total number of tokens.

Step 5: End


## PROGRAM:
 ```
/*
Program to implement a StringBuilder Object Reference in Java
Developed by: Yuvan M
RegisterNumber:  212223240188
*/
```

## Sourcecode.java:

```
import java.util.*;
public class Main
{
    public static void main(String[]args)
  {
        Scanner scan = new Scanner(System.in);
        String name = scan.nextLine();
        StringTokenizer st = new StringTokenizer(name);
        System.out.println("Total number of Tokens: "+st.countTokens());
   }
}


```





## OUTPUT:

<img width="881" height="346" alt="image" src="https://github.com/user-attachments/assets/7203bf5c-e2f8-44a8-a08e-9bbd690e0bc1" />



## RESULT:
Thus the  Java program successfully creates a StringBuilder object using the given string and stores the reference in the variable sb. The contents of the object are printed using the reference variable.

