import java.util.*;
class Income
{
 public static void main(String args[])
 {
 double tax=0,it;
 String name;
 Scanner sc=new Scanner(System.in);
 System.out.print("enter your name:");
 name = sc.nextLine();
 System.out.println("hii!!:" +name);
 System.out.println("Enter your income ");
 it=sc.nextDouble();
 if(it<=200000)
  tax=0;
 else if(it<=300000)
  tax=0.1*(it-200000);
 else if(it<=500000)
  tax=(0.2*(it-300000))+(0.1*100000);
 else if(it<=1000000)
  tax=(0.3*(it-500000))+(0.2*200000)+(0.1*100000);
 else
  tax=(0.4*(it-1000000))+(0.3*500000)+(0.2*200000)+(0.1*100000);
 System.out.println("the tax amount you have to pay is: "+tax);
 }
}
