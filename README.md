# leap-year
import java.util.*;

 // Compiler version JDK 11.0.2

 class Dcoder
 {
   public static void main(String args[])
   { 
     int year;
    System.out.println("enter an year");
    Scanner in=new Scanner (System.in);
    year=in.nextInt();
    
    if(((year%4==0)&&(year%100!=0))||(year%400==0))
 System.out.println("its leap year");
    else
 System.out.println("not a leapyear");
  }
 }
