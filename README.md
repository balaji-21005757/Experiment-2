# Experiment-2
# AIM :
To write a java program to compare two numbers
# ALGORITHM :
1. Open a project in Intelij or any other online java program runner platform
2. Create a class
3. Declare two variables 
4. Using scanner get the inputs for two variables
5. Write the logic to check the comparison of two numbers
6. Run and execute the program
# PROGRAM :
```
import java.util.Scanner;

public class Compare
{
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter first number");
        int x = sc.nextInt();
        System.out.println("Enter second number");
        int y = sc.nextInt();
        System.out.println("By comparing two numbers largest number :");
        if (x > y) {
            System.out.println(x);
        } else {
            System.out.println(y);
        }
        System.out.println("By comparing two numbers smallest number :");
        if (x > y) {
            System.out.println(y);
        } else {
            System.out.println(x);
        }
        System.out.println("By comparing two numbers are equal or not :");
        if (x == y) {
            System.out.println("Equal");
        } else {
            System.out.println("Not equal");
        }
    }
}

```
# OUTPUT:
![image](https://github.com/balaji-21005757/Experiment-2/assets/94372294/a07e3203-3a0f-4740-bab3-d3b52ecc4148)
# RESULT:
Thus a java program to compare two numbers is executed successfully.
