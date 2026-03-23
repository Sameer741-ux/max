import java.util.Scanner;
class max
 {
    public static void main(String[] args)
     {
     int a,b;
     Scanner sc = new Scanner(System.in);
     System.out.println("Entet FirstNumber");
     a= sc.nextInt();
     System.out.println("Enter Second Number");
     b= sc.nextInt();
     if(a>b)
     System.out.println("Max Number="+a);
     else
     System.out.println("Max Number="+b);

     


    }
}
