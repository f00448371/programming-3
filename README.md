# programming-3
import java.util.*;
import java.lang.*;
import java.io.*;
public class VowelDisplay
{
   public static void main(String[] args) 
    {    
      		String sentence ="This is Europe";
        		System.out.println("Vowels:");
      		System.out.println(VowelDisplay.printVowel(sentence));
   }
 Static string printVowel( string s)
    {
       	for(int i=0;i <s.length();i++)
            {
            	if((s.charAt(i) == 'A') || 
                	(s.charAt(i) == 'E') ||
                	(s.charAt(i) == 'I') || 
                	(s.charAt(i) == 'O') ||
                	(s.charAt(i) == 'U')) {
                	System.out.println(s.charAt(i));
            	
            	if((s.charAt(i) == 'a') || 
                	(s.charAt(i) == 'e') ||
                	(s.charAt(i) == 'i') || 
                	(s.charAt(i) == 'o') ||
                	(s.charAt(i) == 'u')) {
                	System.out.println(s.charAt(i));
            }
        }
    }
Output:
Vowels:
i
i
E
u
o
e
Answer2:
import java.util.*;
import java.lang.*;
import java.io.*;

public class ConsonantsDisplay
{
   public static void main(String[] args) 
    {    
      		String sentence ="This is Europe";
        			System.out.println("Consonants:");
      		System.out.println(ConsonantslDisplay.printConsonants(sentence));
	}
 Static String printConsonants( string s)
    {
       		for(int i=0;i <s.length();i++)
            {	
            	if((s.charAt(i) != 'A') || 
                	(s.charAt(i) != 'E') ||
                	(s.charAt(i) != 'I') || 
                	(s.charAt(i) != 'O') ||
                	(s.charAt(i) != 'U')) {
                	System.out.println(s.charAt(i));
            	
            	if((s.charAt(i) != 'a') || 
                	(s.charAt(i) != 'e') ||
                	(s.charAt(i) != 'i') || 
                	(s.charAt(i) != 'o') ||
                	(s.charAt(i) != 'u')) {
                	System.out.println(s.charAt(i));
            }
            
        }
    }

Output:
Consonants:
T
h
s
s
r
p
Answer3:
import java.util.*;
import java.lang.*;
import java.io.*;
class Vowels {
    public static void main(String[] args) {    
        String sentence ="This is E107urope";
        System.out.println("Digits:");
        for(int i=0;i <sentence.length();i++){
            if((sentence.charAt(i)== '0') ||
            	(sentence.charAt(i)== '1') || 
                (sentence.charAt(i)== '2') ||
                (sentence.charAt(i)== '3') || 
                (sentence.charAt(i)== '4') ||
                (sentence.charAt(i)== '5') || 
                (sentence.charAt(i)== '6') ||
                (sentence.charAt(i)== '7') ||
                (sentence.charAt(i)== '8') ||
                (sentence.charAt(i)== '9'))
		 {
                System.out.println(sentence.charAt(i));   
          
            }
        }
    }
}
Output
Digits:
1
0
7

Answer4:
import java.util.*;
import java.lang.*;
import java.io.*;

/* Name of the class has to be "Main" only if the class is public. */
class IntegerValueOfString
{
	public static void main (String[] args)
	{
	 	String str="123";
	 	int len= str.length();
	 	System.out.println(len);
	 	int integervalue= Integer.valueOf(“Length:”+str);
	 	System.out.println(“Converted value”+integervalue);
	}
}
Output:
Length: 3
Converted value: 123
