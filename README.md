# Java---demo
hey! Vaibhav this side
<br>
it's my fisrt code.

import java.util.*;
 public class Vaibhav{

     public static void main(String args[]){
         Scanner sc = new Scanner(System.in);

         System.out.print("enter rows number : ");
         int rows = sc.nextInt();

         System.out.print("enter cols number : ");
         int cols = sc.nextInt();

         int[][]numbers = new int[rows][cols];

         for(int i=0; i<rows; i++){
             for(int j=0; j<cols; j++){

                 System.out.print("enter numbers : ");
                 numbers[i][j] = sc.nextInt();
             }
         }
         System.out.print("enter value where you want to x occurs at : ");
         int x = sc.nextInt();

         for(int i=0; i<rows; i++){
             for(int j=0; j<cols; j++){
                 if(numbers[i][j] == x){
                     System.out.print("x found at this indices : (" + i + "," + j +")");
                 }
             }
         }
     }
 }


