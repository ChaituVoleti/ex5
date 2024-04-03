import java.util.Scanner;

public class Voting {
    public static void main(String[] args) {
        // Declare and initialize variables
        int age, diff;

        // Take user input
        Scanner scan = new Scanner(System.in);
        System.out.println("Please enter your age: ");
        age = scan.nextInt();

        // Check condition for voting
        if (age >= 18) {
            System.out.println("You are eligible for voting.");
        } else {
            diff = 18 - age;
            System.out.println("Sorry, you can vote after " + diff + " years.");
        }
    }
}
