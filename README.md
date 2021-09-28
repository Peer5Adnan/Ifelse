# Ifelse
import java.util.Scanner;
public class Elseif {
    public static void main(String args[]) {
        System.out.println("enter the number one ");
        Scanner reinum = new Scanner(System.in);
        int num1, num2;
        num1 = reinum.nextInt();
        System.out.println("enter number two");
        num2 = reinum.nextInt();
        if (num1 == num2) {
            System.out.println("we are same");
        } else if (num1 >num2) {
            System.out.println(" num1:- I am grater than number 2  " + num1 + ">" + num2);
        } else {
            System.out.println("num2:- I am grater than number 1   " + num2 + "> " + num1);
        }
    }
}
