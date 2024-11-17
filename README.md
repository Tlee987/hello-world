# hello-world
Project 1
public class ComputeMoneyChange
  public static void main{String[] args) ; {
    Scanner input = new Scanner(System.in) ;
*Enter in Amount of Money - Can be any amount with Dollars and cents
    Sysytem.out.print{"Enter a money Amount") ;
    double amount = input.nextDouble() ;
*The following are dollars, Quarters, Dimes, Nickels and Pennies to provide for an answer for the change

    int remainingAmount = (int) (amount * 100) ;
    
    int numberOfOneDollars = remainingAmount / 100;
    remainingAmount = remainingAmount % 100;
* The percentage sign is for the remainder, which is the same for the following, Quarters, Dimes, Nickels and Pennies
* This is an input for any dollar and cents amount, then each amount is remaining between quarters, dimes, nickels and pennies

    int numberOfQuarters = remainingAmount / 25;
    remainingAmount = remainingAmount % 25;

    int numberOfDimes = remainingAmount / 10;
    remainingAmount = remainingAmount % 10;

    int numberOfNickels = remainingAmount / 5;
    remainingAmount = remainingAmount % 5;

    intnumberOfPennies = remainingAmount * 0.01;
    remainingAmount = remainingAmount % 1;
  


    
