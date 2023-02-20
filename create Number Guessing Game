package com.numberGame;
import java.util.*;
public class NumberGuassingGame {
	public static void main(String args[])
    {
        int atmpt = 1;
        int GuessNumber = 0;
        int hiddenNumber = (int) (Math.random() * 99 + 1);          
        Scanner userInput = new Scanner(System.in);
        System.out.println("Welcome to Guess Number Game \nYou Will Be Asked To Guess A Number To Win The Game \nYou have Maximum 5 Attemp Limit");
        do {
            System.out.print("Enter a guess number between 1 to 100\n");
            if(userInput.hasNextInt()) {
                GuessNumber = userInput.nextInt();
                if (GuessNumber == hiddenNumber)
                {    
                    System.out.println("OOhhOO!, Your Number is Correct. You Win the Game! * You are winner*");
                    break;
                }
                else if (GuessNumber < hiddenNumber)
                    System.out.println("Your Guess Number is Smaller.");
                else if (GuessNumber > hiddenNumber)
                    System.out.println("Your Guess Number is Greater.");
                if(atmpt == 5) {
                    System.out.println("You have exceeded the maximum attempt. Try Again");
                    break;
                }
                atmpt++;
            }else {
                System.out.println("Enter a Valid Integer Number");
                break;
            }
        } while (GuessNumber != hiddenNumber);
    }
}
