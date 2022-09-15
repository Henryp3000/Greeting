# Greeting
import java.nio.file.attribute.UserPrincipal;
import java.util.Scanner;

public class Greeting {

  /*
    //    Instructions
//    Understand how to get input from user
//    Create conditional to check against Alice and Bob
//    Print greeting to screen if Alice or Bob are true
     Write a program that asks the user for his/her name and only the users Alice and Bob are greeted with their names.

            Program has to know usernames to greet them
            Need to create a method to call Alice and Bob name
            I can use a loop function
            I could also use a scanner
            I could use a boolean asking Y or N for Alice or Bob
   */

    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.println("Enter your first name:");
        String firstName = input.nextLine();
        if (firstName == "Alice") {
            System.out.println("Hello" + firstName);
        } else if (firstName == "Bob") {
            System.out.println("Hello" + firstName);
        }
    }
}
