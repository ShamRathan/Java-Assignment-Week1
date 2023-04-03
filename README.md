# Java-Assignment-Week1
## Name  : S.Sham Rathan
## Reg.no: 212221230093
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
![1](https://user-images.githubusercontent.com/93587823/224466012-2424f4ea-9047-4624-aea2-7b69badaefb2.jpg)
### 2.Write a Java program to compare two numbers:
```
import java.util.Scanner;
public class compare
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
![2](https://user-images.githubusercontent.com/93587823/224466031-b2e48dc4-cca2-4ea0-9833-b8c16807b82a.png)
### 3. Write a Java program to convert a string to an integer
```
public class string {
    public static void main(String[] args)
    {
        String sc="25";
        int i=Integer.parseInt(sc);
        System.out.println(i);
    }
}

```
![3](https://user-images.githubusercontent.com/93587823/224466045-2c95fc9d-a7ad-468b-ae45-d18dbb183a9e.png)
### 4.Java Program to find area of rhombus 
```
public class area
{
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter diagonal p");
        int p = sc.nextInt();
        System.out.println("Enter diagonal q");
        int q = sc.nextInt();
        int area=(p*q)/2;
        System.out.println("Area of Rhombus:"+area);
    }
}
```
![4](https://user-images.githubusercontent.com/93587823/224466003-9cdf5bba-9532-4f4b-b8af-5d6a302efd71.png)
### 5.Write a Java program to find the number of days in a month
```
import java.util.Scanner;
public class Month {
    public static void main(String[] strings) {
        Scanner input = new Scanner(System.in);
        int number_Of_DaysInMonth = 0;
        String month = input.next();
        switch (month) {
            case "January":
                number_Of_DaysInMonth = 31;
                break;
            case "February":
                number_Of_DaysInMonth = 31;
                break;
            case "March":
                number_Of_DaysInMonth = 31;
                break;
            case "April":
                number_Of_DaysInMonth = 30;
                break;
            case  "May":
                number_Of_DaysInMonth = 31;
                break;
            case "June":
                number_Of_DaysInMonth = 30;
                break;
            case "July":
                number_Of_DaysInMonth = 31;
                break;
            case "August":
                number_Of_DaysInMonth = 31;
                break;
            case  "September":
                number_Of_DaysInMonth = 30;
                break;
            case "October":
                number_Of_DaysInMonth = 31;
                break;
            case "November":
                number_Of_DaysInMonth = 30;
                break;
            case "December":
                number_Of_DaysInMonth = 31;
        }
        System.out.print(month + " has " + number_Of_DaysInMonth + " days\n");
    }
}
```
![5](https://user-images.githubusercontent.com/93587823/224466055-07043ef4-678f-4f56-9e53-9c2217af8e28.png)
### 6.Write a Java program to print the even numbers from 1 to 20
```
public class evennum {
    public static void main(String[] args) {
        for (int i = 2; i <= 20; i += 2) {
            System.out.print(i + " ");
        }
    }
}

```
![6](https://user-images.githubusercontent.com/93587823/224466060-b25709be-8fea-4e7f-acc8-44383be892c6.png)
### 7. Write a Java program to create a simple calculator.
```
import java.util.Scanner;
public class Calculator {
    public static void main(String[] args)
    {
        Scanner s=new Scanner(System.in);
        int re=s.nextInt();
        int se=s.nextInt();
        String sym=s.next();
        switch (sym)
        {
            case "+":
                System.out.println(re+se);
                break;
            case "-":
                System.out.println(re-se);
                break;
            case "*":
                System.out.println(re*se);
                break;
            case "/":
                System.out.println(re/se);
                break;
            case "%":
                System.out.println(re%se);
                break;
            case "&":
                System.out.println(re&se);
                break;
            case "|":
                System.out.println(re|se);
                break;
        }
    }
}

```
![7](https://user-images.githubusercontent.com/93587823/224466081-c650c7c7-7f90-45d3-8ccb-c8f30cba6e8f.png)
### 8.Write a Java program to print multiplication table of a number. 
```
import java.util.Scanner;
public class tables {
    public static void main(String[] args)
    {
        Scanner s=new Scanner(System.in);
        int multab=s.nextInt();
        int n=s.nextInt();
        int i;
        for(i=1;i<=n;i++)
        {
            System.out.println(multab+"*"+i+"="+(multab*i));
        }
    }  }

```
![8](https://user-images.githubusercontent.com/93587823/224466096-4697f1ee-a95b-45fa-88e3-0fd2cec9f993.png)

