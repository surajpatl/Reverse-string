# Reverse-string
package Java;
import java.util.Scanner;

public class Reverse
{

	public static void main(String[] args)
	{
		// TODO Auto-generated method stub
		String str = "Infoway Technology";
		Scanner sc = new Scanner(System.in);
		String revStr = "";
		String[] arr = str.split(" ");
		for (String item : arr) 
		{
			revStr = item + " " + revStr;
		}
		System.out.println("Reverse String= "+ revStr);
	}
}
