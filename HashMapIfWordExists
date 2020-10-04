import java.util.*;

public class Main
{



  public static void main (String[]args)
  {
    Map < String, String > map = new HashMap < String, String > ();
    Scanner input = new Scanner (System.in);
    System.out.print ("Please enter a String! ");
    String s1 = input.nextLine ();
    System.out.print ("Please enter a word! ");
    String s2 = input.nextLine ();
    String[] words = s1.split (" ");
    
    boolean found = false;
    for (int i = 0; i < words.length; i++)
      {

	map.put (words[i], words[i]);
	if (map.containsKey (s2))
	  found = true;
      }


    if (found)
        System.out.println ("The word " + s2 + " is found!");
    if (!found)
      System.out.println ("The word " + s2 + " is not found!");

  }
}
