
# EX 1A Print All Numbers 
## DATE: 04.08.2025
## AIM:
To Write a Java program that takes an integer input N from the user and prints all the numbers from 1 to N, separated by spaces, on a single line..

## Algorithm

1. Start
2. Read input integer n from the user.
3. Initialize a loop variable i to 1.
4. Repeat the following steps while i ≤ n:
5. Print the value of i followed by a space.
6. Increment i by 1.
7. End 

## Program:
```
/*
Developed by: Thaksha Rishi
Register Number:  212223100058
*/

import java.util.*;

public class Main
{
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);
        
        int n = sc.nextInt();
        
        for(int i=1;i<=n;i++)
        {
            System.out.print(i+" ");
        }
    }
}
```

## Output:

<img width="768" height="297" alt="image" src="https://github.com/user-attachments/assets/bf6dab0c-dd85-4c3c-95e4-41377afdf658" />


## Result:
The program successfully print all the numbers from 1 to N. 
