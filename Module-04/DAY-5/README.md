# Ex.No:4(E)  PARAMETERIZED CONSTRUCTOR
## AIM:
To write a parameterized constructor in the Employee class that initializes name and designation, and then call getter methods in the main() method of another class (Sample) to display the values.

## ALGORITHM :
Start

Define class Laptop:

Declare a String variable brand.

Declare a double variable price.

Create a constructor Laptop():

Set brand to "Apple".

Set price to 42500.75.

Define a method getBrand():

Return the value of brand.

Define a method getPrice():

Return the value of price.

Define class Sample:

In the main method:
```
 Create an object myLaptop of class Laptop.
 
 Call getBrand() method using myLaptop and store the result in laptopBrand.
 
 Print laptopBrand.
 
 Call getPrice() method using myLaptop and store the result in laptopPrice.
 
 Print laptopPrice.

```
5.End



## PROGRAM:
 ```
/*
Program to implement a Parameterized Constructor Using Java
Developed by: Yuvan M
RegisterNumber:  212223240188
*/
```

## Sourcecode.java:

```
class Laptop {
    String brand;
    double price;
    public Laptop() {
        this.brand = "Apple";
        this.price = 42500.75;
    }

    public String getBrand() {
        return brand;
    }

    public double getPrice() {
        return price;
    }
}
public class Sample {
    public static void main(String[] args) {
        Laptop myLaptop = new Laptop();
        String laptopBrand = myLaptop.getBrand();
        System.out.println(laptopBrand);
        double laptopPrice = myLaptop.getPrice();
        System.out.println(laptopPrice);
    }
}

```







## OUTPUT:
<img width="393" height="266" alt="image" src="https://github.com/user-attachments/assets/6a3e1814-3e6f-4c04-ba69-a47e15bb1af8" />





## RESULT:
Thus, the  java program was successfully demonstrates the use of a parameterized constructor to initialize class fields.

 


