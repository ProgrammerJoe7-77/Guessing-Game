import java.util.*;
import java.util.Random;


public class GuessingGame {

    public static void main(String[] args) {
        // TODO code application logic here
        Random rand = new Random();
        int number = rand.nextInt(100);
        Scanner scan = new Scanner(System.in);
        int numberOfAttempts = 0;
        boolean win = false;
        
        while (win == false) {
        System.out.println("Enter a guess between 1 and 100: ");
        int guess = scan.nextInt();
        numberOfAttempts++;
        if (guess == number){
            win = true;
            System.out.println("Correct! you guessed the right number!!!");
        }
        else if (guess > number) {
            System.out.println("Your guess was too HIGH! Choose a lower number!");
        }
        else if (guess < number){
            System.out.println("Your guess was too LOW! Choose a higher number");
        }
        }
        
        System.out.println("YOU WIN!!!");
        System.out.println("Game Stats: ");
        System.out.println("Number of tries you attempted: " + numberOfAttempts);
    }
}
