# Ex.No:5(E) HAS-A RELATIONSHIP
## AIM:
To implement a  Java Program to Find the Largest or Max Number in Array using has - a relationship.
## ALGORITHM :

1. Start the program and import Scanner for user input.

2. Create a TriangleArea class with:

   Private variables width and height.
   
   Methods setWidth(double) and setHeight(double) to assign values.
   
   Method getArea() that returns the area by multiplying width and height.

3. In the main method:

   Create a Scanner object and a TriangleArea object.
   
   Read two double inputs from the user (for width and height).

4. Set the width and height in the TriangleArea object and calculate the area.

5. Print the area (after converting it to an integer) and close the scanner.


## PROGRAM:
 ```
/*
Program to implement a HAS-A RelationShip
Developed by: Yuvan M
RegisterNumber:  212223240188
*/
```

## Sourcecode.java:
```
import java.util.Scanner;
public class TriangleArea {

    private double width;
    private double height;

    public void setWidth(double width) {
        this.width = width;
    }

    public void setHeight(double height) {
        this.height = height;
    }

    public double getArea() {
        return width * height;
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        TriangleArea triangle = new TriangleArea();
        double w = sc.nextDouble(); 
        double h = sc.nextDouble(); 
        triangle.setWidth(w);
        triangle.setHeight(h);
        System.out.println((int)triangle.getArea());
    }
}

```






## OUTPUT:
<img width="339" height="372" alt="image" src="https://github.com/user-attachments/assets/a4b69d1d-cc1a-48d6-8b1e-2609759ed39d" />



## RESULT:
Thus the java program to Find the Largest or Max Number in Array using has - a relationship was executed successfully. 

