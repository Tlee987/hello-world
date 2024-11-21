# hello-world
Project 1
public class ComputeMoneyChange
  public static void main(String[] args)  {
    Scanner input = new Scanner(System.in) ;
    System.out.print("Enter a money Amount");
    double amount = input.nextDouble();

    int remainingAmount = (int) (amount * 100);
    
    int numberOfOneDollars = remainingAmount / 100;
    remainingAmount = remainingAmount % 100;

    int numberOfQuarters = remainingAmount / 25;
    remainingAmount = remainingAmount % 25;

    int numberOfDimes = remainingAmount / 10;
    remainingAmount = remainingAmount % 10;

    int numberOfNickels = remainingAmount / 5;
    remainingAmount = remainingAmount % 5;

    int numberOfPennies = remainingAmount * /1;
    remainingAmount = remainingAmount % 1;

    System.out.printIn("Money Amount" + amount + "consists of \n" + numberOfOneDollars + "dollars\n" + numberOfQuarters + = "quarters" + numberOfDimes + " dimes\n" + numberOfNickels + " nickels\n" + remainingAmount numberOfPennies)
; }

