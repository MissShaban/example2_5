# Example2_5
import java.util.*;
public class Example5_2 {
static Scanner console = new Scanner
(System.in);
public static void main(String[] args){ 
System,out.print ("Enter first
string:");
String strl =console.next();
System.out.print ("Enter second
string:");
String str2 = console.next();
if(strl.compareTo(str2) == 0) System.out.println("The two stings are equal.");
if(strl.compareTo(str2) < 0) System.out.println("The sting strl < string str2."); if(strl.compareTo(str2) > 0) System.out.println("The sting strl > string str2.");
}
}
