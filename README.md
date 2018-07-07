# Add2Integer
import java.util.Scanner;  // For keyboard input

public class Add2Integer {   // Save as Add2Integer.java
   public static void main (String[] args) {
      // Declare variables
      int number1, number2, sum;
      Scanner in = new Scanner(System.in);  // Scan the keyboard
      
      // Put up prompting messages and read inputs
      System.out.print("Enter first integer: ");  // prompting message
      number1 = in.nextInt();  // read integer
      System.out.print("Enter second integer: ");
      number2 = in.nextInt();
      
      // Compute sum
      sum = number1 + number2;
      
      // Display result
      System.out.println("The sum is: " + sum);
   }
}
