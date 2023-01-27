# Arrays
import java.util.ArrayList;
import java.util.List;
import java.util.Scanner;
public class Arrays {

	public static void main(String[] args) {
		Scanner input= new Scanner(System.in);
		List<Double> numbers= new ArrayList<>(); 
		
		for(int i=0; i<5; i++) {
			System.out.println("Enter a number:");
			numbers.add(Double.parseDouble(input.nextLine())); 
		}

		System.out.println(numbers);
		double sum=0.0; 
		for(int i=0; i<numbers.size(); i++) {
			sum +=numbers.get(i);
		}
		System.out.printf("Sum: %f ", sum);

	}

}
