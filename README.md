/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package productofarray;
import java.util.Scanner;
/**
 *
 * @author CMD
 */
public class Productofarray {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) 
    {
        int [] arr = new int [] {1, 2, 3, 4, 5};
int sum = 1;
for (int i = 0;i<arr.length; i++) {
sum = sum * arr[i];
}
System.out.println("Sum of all the elements of an array:"+
sum);
}
}
        // TODO code application logic here
    
    

