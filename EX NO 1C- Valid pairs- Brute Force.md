
# EX 1C Valid Pairs using Brute Force Approach
## DATE:11.08.2025
## AIM:
To write a Java program to for given constraints.
Given an integer array nums and an integer k, return the number of pairs (i, j) where i < j such that |nums[i] - nums[j]| == k.

The value of |x| is defined as:

x if x >= 0.
-x if x < 0.

## Algorithm

1. Start  
2. Read the integer `n` (size of the array) and then read `n` integers into the array `nums`.  
3. Read the integer `k` (the required difference).  
4. Use two nested loops:  
   - For each pair of elements `(nums[i], nums[j])` where `i < j`, check if `|nums[i] - nums[j]| == k`.  
   - If true, increment the `count`.  
5. After checking all pairs, print the value of `count` and end.  

## Program:
```
/*

Developed by: Thaksha Rishi
Register Number: 212223100058
*/


import java.util.*;
public class CountPairsWithDifference {
    public static int countKDifference(int[] nums, int k) {
        
        int count=0;
        
        for(int i=0;i<nums.length;i++)
        {
            for(int j=i+1;j<nums.length;j++)
            {
                if(Math.abs(nums[i]-nums[j])==k)
                {
                    count++;
                }
            }
        }
        //Type your code here
        
        
        
            
        
        return count;
    }
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int[] nums = new int[n];
        for (int i = 0; i < n; i++) {
            nums[i] = sc.nextInt();
        }
        int k = sc.nextInt();
        int result = countKDifference(nums, k);
        System.out.println(result);
        sc.close();
    }
}

```

## Output:

<img width="837" height="429" alt="image" src="https://github.com/user-attachments/assets/e9bedbca-ecbb-4ba0-95ab-141fa7be693c" />


## Result:
The program successfully implemented and the expected output is verified.
