# nested_if
decision making
import java.util.Scanner;
class nested_if
{
public static void main(String args[])
{
Scanner s=new Scanner(System.in);
System.out.println("enter the a value:");
int a=s.nextInt();
System.out.println("enter the b value:");
int b=s.nextInt();
System.out.println("enter the c value:");
int c=s.nextInt();

	if(a>b)
	{
		if(a>c)
		{
			if((b>c)&&(b>a))
			{
			System.out.println("b is the biggest");
			}
			else
			{
				System.out.println("a is the biggest");
			}
		}
	else
	{
	System.out.println("c is the biggest");
	}
	}
	
}
