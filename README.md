
import java.util.Scanner;
public class SecondsConverter
{
    public static void main(String[] args)
    {
        Scanner in = new Scanner(System.in);
        
        System.out.println("Enter the number of seconds");
        
        int s = in.nextInt();
        
        System.out.println("Enter the number of minutes");
        
        int m = in.nextInt();
        
        System.out.println("Enter the number of hours");
        
        int h = in.nextInt();
        
        int totalSeconds = s + m *60 + h* 3600 ; 
        
        System.out.println( s + " " + " seconds" + " " + m + " "+ "minutes" + " " + h + " " + "hours" + " " +
        
        totalSeconds + " " + "seconds");
        
        System.out.println(" End of the program");
        

    }
}
