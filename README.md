# Exp2-java
## Aim:
To Code a java program to compare two numbers.
## Algorithm:
### Step1:
Import the required packages.
### Step2:
Get the numbers from the users.
### Step3:
Using if condition compae the numbers.
### Step4:
Display the result.
## Code:
```
import java.util.Scanner;
public class Exp2 {
    public static void main(String[] args)
        {
            Scanner scan=new Scanner(System.in);
            System.out.print("Enter the first number: ");
            int a=scan.nextInt();
            System.out.print("Enter the second number: ");
            int b=scan.nextInt();
            if(a>b)
                System.out.println("A is greater");
            else if(a<b)
                System.out.println("B is greater");
            else
                System.out.println("A is equal to B");
        }
    }
   
   ```
## Output:
![image](https://github.com/Archana2003-Jkumar/Exp2-java/assets/93427594/217b454c-8a9c-4fcd-82b4-2c9bb898ae10)
## Result:
Hence the program has been successfully executed.
