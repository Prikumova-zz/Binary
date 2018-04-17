# Binary
import java.util.Scanner;

public class Binary {

	public static void main(String[] args) {
		Scanner in = new Scanner(System.in);
		short inputNumber = in.nextShort(); //get number by user input
		for (int i = 128; i > 0; i/=2 ) {
			if (inputNumber >=i) {
				System.out.println("1");
				inputNumber -=i;
			}
			else {
				System.out.println("0");
			} //end for this loop
		}

	}

}
