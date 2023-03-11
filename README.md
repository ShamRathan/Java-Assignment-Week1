# Java-Assignment-Week1
### 1.Write a Java program to print the sum, multiply, subtract, divide and remainder of two numbers:
```
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
        int b=sc.nextInt();
        int add=a+b;
        int sub=a-b;
        int mul=a*b;
        int div=a/b;
        int rem=a%b;
        System.out.println("Addition of two numbers:"+add);
        System.out.println("Subtraction of two numbers:"+sub);
        System.out.println("Multiplication of two numbers:"+mul);
        System.out.println("Division of two numbers:"+div);
        System.out.println("Remainder of two numbers:"+rem);
    }
}
```
![output](1.jpg)


