package array;
import java.io.*;
public class Array {

		public static void main(String args[]) throws IOException
	    {
	        int ar[] = { 11, 12, 13, 14, 15, 16, 17, 18 };
	        int i, x;
	        
	        
	        for (i = 0; i < ar.length; i++) {
	  
	            x = ar[i];
	            System.out.print(x + " ");
	        }
	        int firstElement = ar[0];
	        System.out.println("First Element: " + firstElement);

	        
	        int lastElement = ar[ar.length - 1];
	        System.out.println("Last Element: " + lastElement);
	
          ar[2] = 03;

          ar[7] = 24;

    for (int i1 = 0; i1 < ar.length; i1++) {
        System.out.print(ar[i1] + " ");
    }
}
		}
