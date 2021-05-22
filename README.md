   
public class Jala 
{  
	private static final String s = "Sai";   
    
    public static void main(String[] args) 
    {  
        try 
        {  
            System.out.println(s.charAt(4)); 
        }
        catch(StringIndexOutOfBoundsException e)
        {  
            System.out.println("Errorr!!! : "+ e);
        }  
     }  
} 
