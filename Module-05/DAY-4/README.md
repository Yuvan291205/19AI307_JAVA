# Ex.No:5(D) IS-A RELATIONSHIP AND HAS-A RELATIONSHIP
## AIM:
   To Create a java program to find factorial of number using class and object concepts and apply the has-a relationship.
 
## ALGORITHM :
1. Start the program.

2. Create a class Animal with a method eat() that prints "I can eat".

3. Create a class Person that inherits from Animal, and add a method name() that prints "My name is Rohu".

4. Create a Main class that inherits from Person:

   In the main method:
      
      Create an object of Main.
      
      Call name() to print the name.
      
      Call eat() to print the eating ability.

5. End the program.

## PROGRAM:
 ```
/*
Program to implement a IS-A RELATIONSHIP AND HAS-A RELATIONSHIP using Java
Developed by: Yuvan M
RegisterNumber: 212223240188
*/
```

## Sourcecode.java:

```
class Animal {
    public void eat() {
        System.out.println("I can eat");
    }
}

class Person extends Animal {
    public void name() {
        System.out.println("My name is Rohu");
    }
}

public class Main extends Person {
    public static void main(String[] args) {
        Main obj = new Main();
        obj.name();
        obj.eat();
    }
}
```







## OUTPUT:

<img width="434" height="196" alt="image" src="https://github.com/user-attachments/assets/365eac66-58ec-4b6f-ade0-d5e2a606ac91" />


## RESULT:
Thus the java program to find factorial of number using class and object concepts and apply the has-a relationship was executed successfully.
