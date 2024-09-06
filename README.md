# Vending-Machine---JAVA
import java.util.Scanner;
class vendingmachine
{
    public static void main (String[] args)
    {
        Scanner sc = new Scanner (System.in);
        System.out.println("Press 1 for juice and 2 for Soda");
        int choice = sc.nextInt();

        if (choice == 1)
        {
            System.out.println("Dispensing Juice");
        }
        else if (choice == 2)
        {
            System.out.println("Dispensing Soda");
        }
        else {
            System.out.println("Invalid Choice");
        }
        sc.close();

    }
}
