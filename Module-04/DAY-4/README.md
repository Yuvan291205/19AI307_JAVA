# Ex.No:4(D) FINAL & STATIC IN JAVA

## AIM:
   To create a Java program to perform final & static keyword for below situation Employee object contains member 'Emp_Id'. It contains object named name, which contains its own informations such as Fname, Mname, Lname.
 
## ALGORITHM :
1. Start

2. Define class Subject:

   Declare four String variables: subject1, subject2, subject3, subject4.
   
   Define method dispSub(String s1, String s2, String s3, String s4):
   
   Assign s1 to subject1.
   
   Assign s2 to subject2.
   
   Assign s3 to subject3.
   
   Assign s4 to subject4.
   
   Print the four subject names together with spaces between them.

3. Define class Student:

   Declare an int variable Stu_Id.
   
   Create an object sub of the Subject class.
   
   Define method disp(int id, String s1, String s2, String s3, String s4):
   
   Assign id to Stu_Id.
   
   Print Stu_Id.
   
   Call dispSub method of sub object, passing the four subject names s1, s2, s3, and s4.

   Define class Main:

4. In the main method:

   Create an object st of Student class.
   
   Call the disp method on st, passing:
   
   Student ID: 101
   
   Subjects: "Java", "DS", "TOC", "CG"

5. End






## PROGRAM:
 ```
/*
Program to implement a final & Static using Java
Developed by: Yuvan M
RegisterNumber:  212223240188
*/
```

## Sourcecode.java:

```
class Subject {
    String subject1, subject2, subject3, subject4;

    void dispSub(String s1, String s2, String s3, String s4) {
        subject1 = s1;
        subject2 = s2;
        subject3 = s3;
        subject4 = s4;
        System.out.println(subject1 + " " + subject2 + " " + subject3 + " " + subject4);
    }
}

class Student {
    int Stu_Id;
    Subject sub = new Subject();

    void disp(int id, String s1, String s2, String s3, String s4) {
        Stu_Id = id;
        System.out.println(Stu_Id);
        sub.dispSub(s1, s2, s3, s4);
    }
}

public class Main {
    public static void main(String[] args) {
        Student st = new Student();
        st.disp(101, "Java", "DS", "TOC", "CG");
    }
}

```







## OUTPUT:

<img width="459" height="275" alt="image" src="https://github.com/user-attachments/assets/03396f6f-a806-4276-a44a-22656413950b" />



## RESULT:
Thus, the java program to perform final & static keyword was executed successfully.
