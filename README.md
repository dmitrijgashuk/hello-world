import java.util.*;

public class MyClass { 
    public static void main(String args[]) { 
    
    String name = "q2w3e4r5t";

    char[] charArray = name.toCharArray();
    String string = name.replaceAll("[0-9]","");
    
    char[] newString = new char[charArray.length];
    for(int i=0;i<charArray.length;i++){
        if(Character.isDigit(charArray[i])){
            newString[i] = charArray[i];
        }
    }
    int index = newString.length-1;
    ArrayList<Character> list = new ArrayList<Character>(Arrays.asList(newString));
    for(int i=0; i<charArray.length; i++){
        while(!(list.get(index)== null)){
            index--;
        }
        list.set(index, newString[i]);
    }

    }
}
