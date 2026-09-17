
# EX 1A Print All Numbers 
## DATE: 17.09.26
## AIM:
To Write a Java program that takes an integer input N from the user and prints all the numbers from 1 to N, separated by spaces, on a single line..

## Algorithm:

1.Start the program and import the Scanner class to take user input.

2.Create a Scanner object to read an integer input N from the user.

3.Check if N is greater than 0; if not, display "Invalid input. N must be greater than 0."

4.Use a for loop to iterate from 1 to N.

5.Print each number separated by a space on the same line.

## Program:
```
/*
Program to implement Reverse a String
Developed by: SANJEEV RAJ S
Register Number: 212223220096
*/
import java.util.*;
public class PrintNum{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        for(int i=1;i<=n;i++){
            System.out.print(i+" ");
        }
    }
}
```

## Output:

<img width="491" height="159" alt="508013577-ef5e3fdf-c4da-46c2-b207-43343d9ccad8" src="https://github.com/user-attachments/assets/3db58564-bdce-492f-a8c3-5a59925c4a41" />


## Result:
The program successfully print all the numbers from 1 to N. 
