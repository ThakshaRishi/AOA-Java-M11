
# EX 1B Power of 2
## DATE: 07.08.2025
## AIM:
To write a Java program to for given constraints.Given an integer n, return true if it is a power of two. Otherwise, return false.

An integer n is a power of two, if there exists an integer x such that n == 2x.

## Algorithm
1. 
2. 
3. 
4.  
5.   

## Program:
```
/*

Developed by: Thaksha Rishi
Register Number: 212223100058
*/


import java.util.*;

public class Solution {

    public boolean isPowerOfTwo(int n) {
     
     return n>0 && Integer.bitCount(n)==1 ;
     
     
    }

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        Solution sol = new Solution();
        int n = scanner.nextInt();

        boolean result = sol.isPowerOfTwo(n);
        System.out.println(result);

        scanner.close();
    }
}

```

## Output:

<img width="742" height="333" alt="image" src="https://github.com/user-attachments/assets/5d4a95de-4f47-41e1-a5db-ccc0dea486d3" />



## Result:
The program successfully implemented and the expected output is verified.
