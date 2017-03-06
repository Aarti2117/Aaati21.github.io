# Aaati21.github.io
#program 2
import java.util.*;

public class String1 {

	public static void main(String[] args) 
	{
			   String p= "We test coders.Give us a try?Can i try!";
			
			   String[] s = p.split("\\.");
			   String[] s2 = p.split("\\?");
			   String[] s3 = p.split("\\!");

			   List<String> a = new ArrayList<String>();
			   a.addAll(Arrays.asList(s));
			   a.addAll(Arrays.asList(s2));
			   a.addAll(Arrays.asList(s3));
			 
			  Iterator itr=a.iterator();  
			   while(itr.hasNext()){  	   
			    System.out.println(itr.next());  
			   }
			   int retval = a.size();
			   System.out.println("Size of list = " + retval); 
			  }  
	}
