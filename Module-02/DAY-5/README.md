# Ex.No:2(E)  SMALLEST ELEMENT IN AN ARRAY

## AIM:
To write a Java program that reads an array size and elements from the user and then finds and prints the smallest element in the array.
## ALGORITHM :
1.Start

2.Input the size of the array (let's call it size)

3.Create an integer array of length size

4.Loop from i = 0 to size - 1:,Input the i-th element and store it in the array

5.Initialize a variable largest with the first element of the array

6.Loop from i = 1 to size - 1:,If the current element array[i] is greater than largest:,Update largest = array[i]

7.Output the value of largest as the largest element

8.End
	

## PROGRAM:
 ```
/*
Program to implement a Smallest Element in an Array
Developed by: PRAGATHI KUMAR
RegisterNumber:  212224230200
*/
```

## Sourcecode.java:

```
import java.util.Scanner;

public class LargestElement {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        int size = scanner.nextInt();
        int[] array = new int[size];

        for (int i = 0; i < size; i++) {
            array[i] = scanner.nextInt();
        }

        int largest = array[0]; // Assume the first element is the largest initially

        for (int i = 1; i < size; i++) {
            if (array[i] > largest) {
                largest = array[i];
            }
        }

        System.out.println("The largest element in the array is: " + largest);

        scanner.close();
    }
}

```





## OUTPUT:

<img width="902" height="373" alt="image" src="https://github.com/user-attachments/assets/2aeae80a-e550-4b93-a604-36b0ba097981" />


## RESULT:
Thus the java program successfully reads the array size and elements from the user and correctly finds and prints the smallest number in the array.




