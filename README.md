# If..else
import java.util.Scanner;
Public class IFELSE {
    Public static void main(String[]args){ 

                Scanner sc = new Scanner(System.in);
                System.out.println("Enter a number:");
                int n = sc.nextInt();
                if (n>0)
                {
                    System.out.println("The number is Positive");
                }
                else if(n<0)
                {
                    System.out.println("The number is Negative");
                }
                else
                {
                    System.out.println("The number is zero");            
          }
     }
}

OUTPUT:

Enter a number:
0
The number is zero
