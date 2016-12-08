# Assignment9.3

package collectionsdemos;
import java.util.*;

public class HashMap {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		Integer codeOne = new Integer(12);
		Integer codeTwo = new Integer(13);
		Integer codeThree = new Integer(8);
		Integer codeFour = new Integer(17);
		Integer codeFive = new Integer(10);
		
		String  nameOne = new String("ramesh");
		String  nameTwo = new String("vinod");
		String  nameThree = new String("Satheesh"); 
		String  nameFour = new String("vishnav");
		String  nameFive  = new String("manju");
		
		HashMap<Integer,String> maps = new HashMap<Integer,String>();  

        maps.put(codeOne,nameOne);
        maps.put(codeTwo,nameTwo);
        maps.put(codeThree,nameThree);
        maps.put(codeFour,nameFour);
        maps.put(codeFive,nameFive);
        for(Map.Entry m:maps.entrySet()){  
        	System.out.println(m.getKey());
        }
       
        }
	}
