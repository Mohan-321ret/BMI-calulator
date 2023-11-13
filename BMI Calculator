import java.util.Scanner;

public class bmicalculation {
    //main method
    public static void main(String[] args) {
        //scanner for reading input from user
        Scanner input = new Scanner(System.in);

        System.out.println("BMI Calculator");
        System.out.print("Enter your weight in kilograms: ");
        double weight = input.nextDouble();

        System.out.print("Enter your height in meters: ");
        double height = input.nextDouble();

        double bmi = calculateBMI(weight, height);
        String interpretation = interpretBMIvalue(bmi);

        System.out.println("Your Body Mass Index is: " + bmi);
        System.out.println("Interpretation: " + interpretation);

        input.close();
    }

    // formula for calculating BMI (bmi = weight/height*height)
    public static double calculateBMI(double weight, double height) {
        return weight / (height * height);
    }

    // function for interpret BMI value
    public static String interpretBMIvalue(double bmi) {
        if (bmi  < 18.5) {
            return "Underweight";
        } else if (bmi >= 18.5 && bmi < 24.9) {
            return "Healthy weight";
        } else if (bmi >= 25 && bmi < 29.9) {
            return "Overweight";
        }  else {
            return "Obesity";
        }
    }
}
