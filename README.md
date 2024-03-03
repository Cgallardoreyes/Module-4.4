# Module-4.4import java.util.Scanner;
public class CalculateHexagonArea {
    public static void main(String[] args) {
        // Create a Scanner object to read user input
        Scanner scnr = new Scanner(System.in);
        // Prompt the user to enter the side length of the hexagon
        System.out.print("Enter the side: ");
        double side = scnr.nextDouble();
        // Calculate the area of the hexagon using the formula
        double area = (6 * side * side) / (4 * Math.tan(Math.PI / 6));
        // Display the calculated area
        System.out.printf("The area of the hexagon is %.2f", area);
        // Close the scanner
        scnr.close();
    }
}
