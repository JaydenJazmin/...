import java.util.Scanner;
public class Ex1{
    public static void main(String [] args){
        Scanner scanner=new Scanner(System.in);
		
			System.out.print("Enter your Weight(kg):");
			double weight=scanner.nextDouble();		   	    	
			System.out.print("Enter your Height(m):");
			double height=scanner.nextDouble();
			
			double BMI=Math.round(weight/height/height*100.0)/100.0;
			System.out.println("Your BMI is "+BMI);
			
			if(BMI<=18.4) {
				System.out.println("Your BMI is Underweight");
			}
			else if(BMI>=18.5 && BMI<=24.9) {
				System.out.println("Your BMI is Normal");
			}
			else if(BMI>=25.0 && BMI<=39.9) {
				System.out.println("Your BMI is Overweight");
			}
			else {
				System.out.println("Your BMI is Obsese");
			}
    }
}
