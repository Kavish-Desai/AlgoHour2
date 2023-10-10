import java.util.Scanner;


public class Solution{
    public static void main(String[] args)
    {
      Scanner input = new Scanner(System.in);
      System.out.println("Enter a number: ");
      int num1= input.nextInt();

      System.out.println(isPrime(num1));
    }
    public static boolean isPrime(int number) {
    if (number <= 1 || number % 2 == 0) {
        return false;
    }
    for (int i = 2; i <= Math.sqrt(number); i++) {
        if (number % i == 0) {
            return false;
        }
    }
    return true;
}
}  
