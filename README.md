# GreatestNumber
import java.util.Scanner;

public class LargestNumberAmongThreeInput { public static void main(String []arg) {

Scanner get=new Scanner(System.in);
System.out.println("enter Integer A"); 
int A=get.nextInt();
System.out.println("enter Integer B"); 
int B=get.nextInt();
System.out.println("enter Integer C"); 
int c=get.nextInt();
if(A>B && A>c)
{
    System.out.println("A is greater");
}
else if(B>A && B>c)
{
    System.out.println("B is greater");
}
else
{
    System.out.println("C is greater");
}

}

}
