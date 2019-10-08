import java.util.Scanner;
public class stringReverse {
  public static void main(String[] args) {
    Scanner temp = new Scanner(System.in);
    System.out.print("Enter string to be reversed: ");
    String toBeReversed = temp.nextLine();
    System.out.println(reverse(toBeReversed));
  }
  public static String reverse(String x) {
    //Base Case
    if(x.equals("")) {
      return "";
    }
    //Recursive Case
    return reverse(x.substring(1)) + x.charAt(0);
  }
}
