# Take-n-as-input-and-print-the-sum-of-numbers-from-1-to-n.
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter a number: ");
        int n = sc.nextInt();

        int sum = 0;

        // Loop from 1 to n and add each number to sum
        for (int i = 1; i <= n; i++) {
            sum += i;
        }

        System.out.println("Sum from 1 to " + n + " is: " + sum);
    }
}
