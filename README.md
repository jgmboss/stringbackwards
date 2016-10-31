import java.util.Scanner;
public class stringbackwards
{
 public static void main (String [] arg){
 Scanner input = new Scanner (System.in);
 
 System.out.println ("Please enter anything");
 
 String reverseString = ""; // to store reverse string 
 
 String s = input.nextLine(); // get string user
 
 for (int i = s.length()-1; i >= 0; i--)
 {
     reverseString = reverseString + s.charAt(i);
    
 }
 
 System.out.println ("Your reverse string is ");
 System.out.println (reverseString);
}
}
