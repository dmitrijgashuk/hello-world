import java.util.*;

public class MyClass {
    public static void main(String args[]) {
        String name = "q2w3e4r5t6y7ui8";

        System.out.println(name);
   
        char[] charArray = name.toCharArray();
        String newString = name.replaceAll("[0-9]","");
        
        ArrayList<Character> list = new ArrayList<>(Arrays.asList(charArray));
        
         

        
        //for(int i=0;i<list.size();i++){
          //  System.out.print(list.get(i)+" ");
        //}

    }
}
