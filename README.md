# FtoC
import java.util.Scanner;

public class Program {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		float f,c;
		Scanner sc = new Scanner(System.in);
		System.out.println("Enter a temperature in Degrees Fahrenheit");
		f = sc.nextFloat();
		
		c = (f-32)*5/9;
		
		System.out.println("That's " + c + " degrees Celsius");

	}

}
