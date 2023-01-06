//Tokenizer
import java.util.*;

class token

{ public static void main(String args[])

    { Scanner sc =new Scanner(System.in);

        System.out.println("enter the digits with space in between ");

      String digit =sc.nextLine();

      StringTokenizer token =new StringTokenizer(digit);

      int dig=0,sum=0;

      System.out.println("enter the digits :");

      while(token.hasMoreTokens())

        {

            String s =token.nextToken();

            dig=Integer.parseInt(s);

            sum=sum+dig;

        }

        System.out.println("sum="+sum);

    }

}






//frequency
import java.util.Scanner;
class freq
{public static void main(String args[])
  {String input;
  int count=0;
  Scanner sc=new Scanner(System.in);
  System.out.println("Enter string:");
  input=sc.nextLine();
  String copy=input.toLowerCase();
  System.out.println("Character to search:");
  char charToSearch=sc.next().charAt(0);
  char charToSearchCopy=Character.toLowerCase(charToSearch);
  char array[]=copy.toCharArray();
  for(char ch:array)
  	{if(ch==charToSearchCopy)
  		{count++;
  		}
  	}
  System.out.println("freq of character "+charToSearch+"  is  "+count);
  }	
}







//Matrixmulti

