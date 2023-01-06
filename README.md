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

