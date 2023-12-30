README.md# lab3+.all.ex
/*
* student name: Mashhour alzahrani
* ID: 44511289
* group: 144
*
*/

exercise 1
import java.util.Scanner; 
public class lab3plas {
    public static void main(String[] args) {
        // Prompt user for input
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter temperature in Fahrenheit: ");

        // Read Fahrenheit temperature as an integer
        int fahrenheit = scanner.nextInt();

        // Convert Fahrenheit to Celsius using the formula
        double celsius = (fahrenheit - 32) * 5.0/9.0;

exercise 2
import java.util.Scanner;

public class lab3plas {
    public static void main(String[] args) {
        // Prompt user for input in SAR
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter amount in Saudi Riyal (SAR): ");

        // Read SAR amount as a double
        double sarAmount = scanner.nextDouble();

        // Conversion rates
        double sarToUsdRate = 0.27;
        double usdToKwdRate = 0.30;

        // Convert SAR to USD
        double usdAmount = sarAmount * sarToUsdRate;
        System.out.println("Converted to USD: " + usdAmount + " USD");

        // Convert USD to KWD
        double kwdAmount = usdAmount * usdToKwdRate;
        System.out.println("Converted to Kuwaiti Dinar (KWD): " + kwdAmount + " KWD");

        // Close the scanner
        scanner.close();
    }
}
exercise 3
import java.util.Scanner;

public class lab3plas {
    public static void main(String[] args) {
        // Prompt user for input
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter the market price of the clothes: ");

        // Read market price as a double
        double marketPrice = scanner.nextDouble();

        // Calculate discount (35%)
        double discountPercentage = 0.35;
        double discountAmount = marketPrice * discountPercentage;

        // Calculate discounted price
        double discountedPrice = marketPrice - discountAmount;

        // Display the result
        System.out.println("Discounted price after applying 35% discount: " + discountedPrice);

        // Close the scanner
        scanner.close();
    }
}
exercise 4
import java.util.Scanner;

public class lab3plas {
    public static void main(String[] args) {
        // Prompt user for input
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter the radius of the circle as an integer: ");

        // Read radius as an integer
        int radius = scanner.nextInt();

        // Constant value for π
        final double PI = 3.14159;

        // Calculate circle properties
        double diameter = 2 * radius;
        double circumference = 2 * PI * radius;
        double area = PI * Math.pow(radius, 2);

        // Display the results
        System.out.println("Diameter: " + diameter);
        System.out.println("Circumference: " + circumference);
        System.out.println("Area: " + area);

        // Close the scanner
        scanner.close();
    }
}






















































        

        // Display the result
        System.out.println("Temperature in Celsius: " + celsius);

        // Close the scanner
        scanner.close();
    }
}
