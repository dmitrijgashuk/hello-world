# hello-world
//Just first repository
import java.util.*;

public class MyClass {
    public static void main(String args[]) {
        String s = "q2w3e4r5t6y7ui8";
        String m = s.replaceAll("[0-9]","");
        System.out.println(s);
   
        reversString(m);
    
        }
        
    }
    
    public static void reversString (String name){
        char[] charArray = name.toCharArray();
        
        ArrayList<Character> list = new ArrayList<>();
        
            for(int i=0;i<charArray.length; i++){
            if(Character.isDigit(charArray[i])){
                revers[i]=charArray[i];
            }else list.add(0,charArray[i]);
        }
        String toString;
        
        for(int i=0;0<list.size();i++){
            System.out.print(list.get(i)+" ");
        }

    }
}
