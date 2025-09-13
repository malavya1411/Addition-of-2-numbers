```java
import java.util.Scanner;

class main
{
   public static void main(String[]args)
{
   Scanner sc= new Scanner(System.in);
   int a,b,c,d,e;
   System.out.print("Enter first number:");
   a=sc.nextInt();
   System.out.print("Enter second number:");
   b=sc.nextInt();
   c=a+b;
   d=a*b;
   e=a-b;
   System.out.println("Sum is :"+c);
   System.out.println("Multiplication is :"+d);
   System.out.println("Substraction is:"+e);
}
}
