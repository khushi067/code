# code
codes of java
// To write a program in java with a class Rectangle with the data fields width, length, area and colour. The length, width and area are of double type and
colour is of string type.The methods are get_length(), get_width(), get_colour() and
find_area().
Create two objects of Rectangle and compare their area and colour. If the area and
colour both are the same for the objects then display “Matching Rectangles”,
otherwise display “Non-matching Rectangle”.
  
import java.io.*;
import java.util.*;
class Rect
  {
     double width,length,area;
      String colour;
     Scanner sc=new Scanner(System.in);
      
      Rect()
        {
              system.out.println("Enter the length: ");
              length=sc.nextDouble();

              system.out.println("Enter the width: ");
             width=sc.nextDouble();       

              system.out.println("Enter the color: ");
             color=sc.next();       

            area =length*width;
            system.out.println("Area of Rectangle: "+area); 
           
           }
  }
      
 class Demo 
     {
        public static void main(String args[])
           {
               system.out.println("First Rectangle ");
                Rect r1=new Rect();

               system.out.println("Second Rectangle ");
                Rect r2=new Rect();
           
          if (r1.area==r2.area && r1.color.equals(r2.color))
                 
                      system.out.println("Matching Recangle: ");
         else
                      system.out.println("Non Matching Recangle: ");  

}

}
